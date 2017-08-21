[circle.ci-master-badge]: https://circleci.com/gh/eugene-matvejev/battleship-game-api-json-schema/tree/master.svg?style=svg
[circle.ci-master-link]: https://circleci.com/gh/eugene-matvejev/battleship-game-api-json-schema/tree/master

|                     | master
|---                  |---
| __mock validation__ |
| _< Circle CI >_     | [![build][circle.ci-master-badge]][circle.ci-master-link]


# Battleship Game API responses/requests JSON schemas
the purpose of this repository is to store JSON schemas for the API responses|requests of the [battleship-game-api](https://github.com/eugene-matvejev/battleship-game-api) as well as some hard-coded mocks which represets business logic _as schema can't always represent business logic_

so whenever you're testing front-end or back-end you can relay on schemas and mocks - instead of using real back-end for request/receive data

_every JSON file is stored in_ '__PRETTY' format__

mocks are validated against schema on every Pull Request | Commit

## THIS IS SPARE TIME PROJECT, WORK IN PROGRESS! HIGHLY EXPERIMENTAL!!!
## used technologies
 * node.js
 * jest
 * npm
 * yarn
 * composer
 * json
 * json schema

## how to install
* php, composer
 composer provides opportunity to checkout [additional sources of the packages](https://getcomposer.org/doc/05-repositories.md#loading-a-package-from-a-vcs-repository)
 add another source into your __composer.json__:
 ```
 repositories": [
     { "type": "vcs", "url": "https://github.com/eugene-matvejev/battleship-game-api-json-schema" }
 ],
 ```
 `$ composer install eugene-matvejev/battleship-game-api-json-schema` consider use `--dev` flag to add in _devDependencies_ section

## how to run tests
 * `$ npm test`
