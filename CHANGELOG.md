# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).


## [0.0] - 2017-04-14
### Added
- PROJECT SET UP, created new files:
  1. readme
  2. changelog.md
  3. .gitignore
  4. server/server.js

## [0.1] - 2017-04-14
### Added
- created basic server.js file, without passport or routes.

## [0.2] - 2017-04-14
### Added
- added a mongo connection index.js file that returns a promise

## [0.3] - 2017-04-14
### Added
- added server tests
### BUGS // TO DO
- need to create a testing database && easy way to drop & restart

## [0.4] - 2017-04-14
### Added
- added separate testing database, connection files etc.

## [0.5] - 2017-04-14
### Added
- set up Travis CI testing

## [0.6] - 2017-04-15
### Added
- set up views, bootstrapped some login / registration pages

## [0.7] - 2017-04-15
### Added
- added client-side js for form handling etc

## [0.8] - 2017-04-15
- messed up, experimental version

## [0.9] - 2017-04-15
### Added
- working Beta version of the JWT authenticated paths without passport!
- added a demo gif

## [1.0] - 2017-04-17
### Added
- added bcrypt for hashing passwords and saving them in mongo db

## [1.1] - 2017-04-18
### Added
- Saving the token in a cookie now, so token gets sent to server on every request.
- refactored client-side js, much simpler and one file
- refactored auth middleware, so user info gets saved in `req.user` after getting verified
### BUGS
- need to clear cache after user logs out

## [jwt-cookies-v1] - 2017-04-18
### FIXES
- fixed clear cache bug
## TO DO
- form validation on client side