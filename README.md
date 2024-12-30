# Walk the Dog
## Description
Current State: 
A red hat boy who can run, jump, and slide to avoid obstacles.
My goal:
An endless runner where you play as a boy walking his dog through the forest when your dog is surprised by the cat that runs by and starts chasing it. You then begin chasing your dog through the forest, dodging obstacles along the way, until you crash into one and fall down. At which point the dog turns around to check on you (obviously).

## How to play
### Movements
* Right arrow key: To run forward
* Down arrow key: To butt slide
* Space bar: To jump

## Specs
* Updating at 60 fps
* fixed step game loop
* Recognizes arrow down, space, and right
* Hanna-Barbera technique for background

## How to install

```sh
npm install
```

## How to run in debug mode

```sh
# Builds the project and opens it in a new browser tab. Auto-reloads when the project changes.
npm start
```

## How to build in release mode

```sh
# Builds the project and places it into the `dist` folder.
npm run build
```

## How to run unit tests

```sh
# Runs tests in Firefox
npm test -- --firefox

# Runs tests in Chrome
npm test -- --chrome

# Runs tests in Safari
npm test -- --safari
```

## What does each file do?

* `Cargo.toml` contains the standard Rust metadata. You put your Rust dependencies in here. You must change this file with your details (name, description, version, authors, categories)

* `package.json` contains the standard npm metadata. You put your JavaScript dependencies in here. You must change this file with your details (author, name, version)

* `webpack.config.js` contains the Webpack configuration. You shouldn't need to change this, unless you have very special needs.

* The `js` folder contains your JavaScript code (`index.js` is used to hook everything into Webpack, you don't need to change it).

* The `src` folder contains your Rust code.

* The `static` folder contains any files that you want copied as-is into the final build. It contains an `index.html` file which loads the `index.js` file.

* The `tests` folder contains your Rust unit tests.


## Tools
* Rust Nighly: rustc 1.87.0-nightly
* Node Version: Nodejs 16.13.0