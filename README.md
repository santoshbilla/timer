# Timer

A basic timer that will start a countdown based on an input of time in seconds.

The Timer provides start, stop, and rest functionality. When the timer reaches a value <= 10, the timer color changes to red.

Go **[here](http://react-timer-basic.drminnaar.me/)** for live demo.

Component Diagram
![](https://user-images.githubusercontent.com/33935506/34461426-30e5547c-ee32-11e7-8889-4fd16df7a7bb.png)

This project also demonstrates:

* a typcial React project layout structure
* babel setup and configuration
* webpack setup and configuration
* eslint setup and configuration
* SCSS setup and configuration


---

## Developed With

* [Node.js](https://nodejs.org/en/) - Javascript runtime
* [React](https://reactjs.org/) - A javascript library for building user interfaces
* [Babel](https://babeljs.io/) - A transpiler for javascript
* [Webpack](https://webpack.js.org/) - A module bundler
* [SCSS](http://sass-lang.com/) - A css metalanguage
* [Bootstrap 4](https://getbootstrap.com/) - Bootstrap is an open source toolkit for developing with HTML, CSS, and JS
* [Surge] - Static web publishing for Front-End Developers

---



## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

The following software is required to be installed on your system:

* Node 8.x
* Npm 3.x

Type the following commands in the terminal to verify your node and npm versions

```bash
node -v
npm -v
```

### Install

Follow the following steps to get development environment running.

* Clone _'react-timer-basic'_ repository from GitHub

  ```bash
  git clone 
  ```

* Install node modules

   ```bash
   cd react-timer-basic
   npm install
   npm dedupe
   ```

### Build

* Build application

  This command will also run ESLint as part of build process.

  ```bash
  npm run build
  ```

* Build application and start watching for changes

  This command will also run ESLint as part of build process.

  ```bash
  npm run build:watch
  ```

### Run ESlint

* Lint project using ESLint

  ```bash
  npm run lint
  ```

* Lint project using ESLint, and autofix

  ```bash
  npm run lint:fix
  ```

### Run

* Run start

  This will run the _'serve'_ npm task

  ```bash
  npm start
  ```

* Run webpack dev server

  ```bash
  npm run serve:dev
  ```

* Alternatively run live-server (simple development http server with live reload capability)

  ```bash
  npm run serve
  ```

---

