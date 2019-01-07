# The Express Express

## Setup

Do all of your work in one file (`server.js`). No need to break things out into other files.

- [x] You already have a `package.json` which means you **don't** need to type `npm init`
- [X] Bring `express` into your project using `npm intall express --save` in terminal
- [X] Setup your `server.js` to serve static files
- [X] Run your server with `npm start`
- [X] Your application should run on `localhost:5000` (**do not**) open your `index.html` directly

> NOTE: When making changes to your `server.js` file, you must **stop** (`ctrl-c`) and re-**start** (`npm start`) your server for changes display in your browser.

## Base

- [X] `localhost:5000/train` should return the list of all trains
- [X] `localhost:5000/first-train` should return the first train object in the array
- [X] `localhost:5000/last-train` should return the last train object in the array

## Stretch

- [X] `localhost:5000/count` should return the number of trains in the array
- [X] `localhost:5000/random` should return a random train object in the array
- [ ] `Moment.js` is a common javascript module used for time. `npm install moment` and use it to show the time of the next train. Trains run every ten minutes starting at the top of the hour. So visiting `localhost:5000/next` at 2:35pm should should `2:40pm` as the result. *This one is tricky!* We'll talk more about `Moment.js` later.
