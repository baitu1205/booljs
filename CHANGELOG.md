<a href="http://booljs.co"><img width="200px" src="https://cdn.rawgit.com/BoolJS/booljs/master/logo.svg" alt="Bool.js" /></a>

_Changelog_

### 0.6.2

* Now CLI resides in [`booljs-cli`](https://npmjs.com/package/booljs-cli).

### 0.6.1

* Updated booljs-api: Fixed an error where plugin's dependencies weren't being loaded.

## 0.6.0: (I Can't Get No) Satisfaction
[_10 May 2016_](https://github.com/BoolJS/booljs/commits/v0.6.0)

<img alt="(I Can't Get No) Satisfaction" src="http://eurohittop40.ru/images/discs/31509/31509.jpg" height="300px">

* Changes in the way plugins are:
  - Defined
  - Loaded
  - Stored
* Gives more responsibilities to the application instance.
* Enfoces plugins to be peer dependent from API module instead of referencing to `bool.js/api`.
* Changes the way dependencies are loaded into bool.js
* Deprecate integrity checking method in plugins. Now is done internally.

_Side notes_ We welcome [@winos](https://github.com/winos) to the Bool.js team. As the greatest contributor in this iteration, he named this version.

### 0.5.9

* Updated booljs-api
* Sort RouteMiddleware after selecting it. Use following criteria:
  * Priority
  * Name

### 0.5.8

* Updated booljs-express

### 0.5.7

* Fix- booljs-cors was having issues when sending extra headers. Fixed

### 0.5.6

* Update booljs-express

### 0.5.5

* Minor fix in booljs-express

### 0.5.4

* [booljs-express] Add suport for bodyParser options

### 0.5.3

* [booljs-express] Fix at json view

### 0.5.2

* Fixed issue on listing Middleware plugins.

### 0.5.1

* Fix the way middleware was being loaded in booljs bootstraping process.

## 0.5.0: People Are Strange
[_24 December 2015_](https://github.com/BoolJS/booljs/commits/v0.5.0)

<img alt="The Doors" src="https://d33goyr6pqlwpd.cloudfront.net/sites/thedoors/files/song_images/SD_USA-PeopleAreStrange7InchSleeve_IMPU09.jpg" height="300px">

* Updated to latest spec of API, now bool.js is in charge of preparing middleware, route lists and passing them to ServerLoaders.

### 0.4.4

* Fixed bug in `booljs-express` where non-existing file caused undefined reference errors.

### 0.4.3

* Updated `booljs-express` to allow configure server settings through `server` configuration file.

### 0.4.2

* Fix issue when loading folders

### 0.4.1

* Fixed issue in **booljs-express**. Applying dependency update.

## 0.4.0: Banana Smoothie
[_3 November 2015_](https://github.com/BoolJS/booljs/commits/v0.4.0)

<img alt="Naked Brothers Band" src="https://upload.wikimedia.org/wikipedia/en/b/b0/NBB_Album_Cover.jpg" height="300px">

* Using new API resources
* Instantiating utilities in bootstrapping process
* Validating Data Loaders

### 0.3.5
[_28 October 2015_](https://github.com/BoolJS/booljs/commits/v0.3.5)

* Lock run() process until previous instance finish it.

### 0.3.4
[_28 October 2015_](https://github.com/BoolJS/booljs/commits/v0.3.4)

* Changed loading order to boot components before database and server.

### 0.3.3
[_26 September 2015_](https://github.com/BoolJS/booljs/commits/v0.3.3)

* Updated CLI

### 0.3.2
[_22 September 2015_](https://github.com/BoolJS/booljs/commits/v0.3.2)

* Update dependencies

### 0.3.1
[_22 September 2015_](https://github.com/BoolJS/booljs/commits/v0.3.1)

* Updated dependencies

## 0.3.0: Everybody's Changing
[_22 September 2015_](https://github.com/BoolJS/booljs/commits/v0.3.0)

<img alt="Hopes And Fears" src="https://ia700702.us.archive.org/0/items/mbid-df6d6bc4-53c1-43e8-9008-a52e6c2c9852/mbid-df6d6bc4-53c1-43e8-9008-a52e6c2c9852-6784289434.jpg" height="300px">

* New endpoint to allow plugins use integrated API version, instead of global (use this with caution).
* Plugins store improved.

### 0.2.2
[_22 September 2015_](https://github.com/BoolJS/booljs/commits/v0.2.2)

* Fix dependencies issue in API call

### 0.2.1
[_22 September 2015_](https://github.com/BoolJS/booljs/commits/v0.2.1)

* Updated API

## 0.2.0: It's The End Of The World As We Know It (And I Feel Fine)
[_22 September 2015_](https://github.com/BoolJS/booljs/commits/v0.2.0)

<img alt="It's The End Of The World As We Know It (And I Feel Fine)" src="https://ia802709.us.archive.org/26/items/mbid-30e4cd2e-1d3e-4e43-bc44-8cb3395102e5/mbid-30e4cd2e-1d3e-4e43-bc44-8cb3395102e5-2647873120.jpg" height="300px">

* Implemented plugins from API
* Better support for more providers

### 0.1.7
[_15 September 2015_](https://github.com/BoolJS/booljs/commits/v0.1.7)

* Passing tests with updated dependencies

### 0.1.6-pre
[_15 September 2015_](https://github.com/BoolJS/booljs/commits/v0.1.6-pre)

* Testing version to evaluate API updates

### 0.1.5
[_13 September 2015_](https://github.com/BoolJS/booljs/commits/v0.1.5)

* Added CLI client

### 0.1.4
[_12 September 2015_](https://github.com/BoolJS/booljs/commits/v0.1.4)

* Updated dependencies and documentation

### 0.1.3
[_12 September 2015_](https://github.com/BoolJS/booljs/commits/v0.1.3)

* Updated dependencies

### 0.1.2
[_11 September 2015_](https://github.com/BoolJS/booljs/commits/v0.1.2)

* Set features for testing

### 0.1.1
[_11 September 2015_](https://github.com/BoolJS/booljs/commits/v0.1.1)

* Support connections on model fetcher

## 0.1.0: All Together Now
[_10 September 2015_](https://github.com/BoolJS/booljs/commits/v0.1.0)

<img alt="Yellow Submarine" src="https://ia800306.us.archive.org/27/items/mbid-98a627c2-190f-4bcc-a90c-459462dbf67b/mbid-98a627c2-190f-4bcc-a90c-459462dbf67b-1229882757.jpg" height="300px">

* Using functional API.
* Successfully loading project structure.
* Supporting database and server drivers.

### 0.0.6
[_10 September 2015_](https://github.com/BoolJS/booljs/commits/v0.0.6)

* Now loading models and components

### 0.0.5
[_10 September 2015_](https://github.com/BoolJS/booljs/commits/v0.0.5)

* Now loading models and components

### 0.0.4
[_8 June 2015_](https://github.com/BoolJS/booljs/commits/v0.0.4)

* Minor update in NPM

### 0.0.3
[_14 May 2015_](https://github.com/BoolJS/booljs/commits/v0.0.3)

* Minor update in NPM

### 0.0.2
[_14 May 2015_](https://github.com/BoolJS/booljs/commits/v0.0.2)

* Minor update in NPM

### 0.0.1
[_14 May 2015_](https://github.com/BoolJS/booljs/commits/v0.0.1)

* Initial version
