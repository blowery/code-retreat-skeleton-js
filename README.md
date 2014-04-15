# Code Retreat JavaScript Skeleton

## Installation

First, install Node.js.

Then, run

```
$ npm install
```

in the repository directory.

You can confirm it’s working by running:

```
$ npm test
```

## Writing Tests

This primer uses [Mocha](http://visionmedia.github.io/mocha/). The project website has good and consice documentation about how it works.

Asserts are done via the [better-assert](https://github.com/visionmedia/better-assert) library, which is very straight-forward, just pass a boolean value.

The game of life code is short enough so that it’s fine if we write both the code and the tests in the same file.

## Running Tests

```
$ npm test
```

## Starting a New Session

Deleting code is hard on the mind, but not hard on the console. Just run:

```
$ npm run-script reset
```

**WARGNING:** This will **permanently** delete all modifications after the previous commit.
