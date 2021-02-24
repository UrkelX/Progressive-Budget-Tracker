# Progressive-Budget-Tracker


## Description
An app that allows users to add and subtract amounts from a total. This app will work online and offline. Transactions that happen offline will save and be displayed online when the app reconnects to the network. 

## Table of Contents

* [Installation](#installation)

* [Code](#code)

* [Usage](#usage)

* [Contributions](#contributions)

* [Tests](#tests)

* [License](#license)

* [Contact](#contact)

## Installation
To run app you must install:
* dotenv

## Code
```
self.addEventListener("install", function (evt) {
  evt.waitUntil(
    caches.open(CACHE_NAME).then((cache) => {
      console.log("Your files were successfully pre-cached");
      return cache.addAll(FILES_TO_CACHE);
    })
  );

  self.skipWaiting();
});
```


## Usage

See sample here:
![BT](https://user-images.githubusercontent.com/70240665/108940610-480cf200-7619-11eb-9d71-6e61795ba875.png)



## Contributions
Thank you for the support from my TAs, instructor, and classmates.

To contribute, please reach out.

## Tests
N/A

## Deployed 
[Heroku](https://secure-meadow-28586.herokuapp.com/)

## License
[MIT License](https://github.com/UrkelX/README_Generator/files/5646505/MIT.txt)


## Contact
GitHub: @[UrkelX](https://github.com/UrkelX)

Email: jordon@blackbirdrevolt.com