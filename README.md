# \<guess-my-number\>

Guess a number

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

## Running End-to-end Tests

Note: you need a recent version of Java SE installed on your machine to run the end to end tests.

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

## Deploying to Firebase

Warning: a specific account has been setup to deploy to Firebase hosting. You will need to change the configuration of `.firebaserc` to point to your own Firebase account.

Note: it's necessary to build first because it's the build/default directory that will be published to Firebase, according to the rules set out in the configuration file `firebase.json`

```
$ polymer build
$ firebase deploy
```

Navigate to https://which-number.firebaseapp.com/

## Development

During development, the src files are used instead of the generated ones from build/default.

```
polymer serve
```

## Contribute to this project's repository

Fork the repository on Github, create a branch with a name representative of what you are improving or fixing in the code and raise a pull request to be merged back to the develop branch of this repository.
