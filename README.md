# React Express Airbnb Template
A starter kit for building React-Express Applications. Devdependencies utilize airbnb-eslint settings and integrate prettier plugin from VScode.

# Usage

1. `npm i -g nodemon` (a utility that monitor for any changes in your source and automatically restarter your server)
2. `npm i && cd client && npm i` (install the dependencies and devdependencies)
3. Install prettier and eslint plugin in VScode extension.
4. `npm run test` to run the Express server and serve your React front-end. The server is running on `localhost:8080` and the proxy is set to the same address in `/client/package.json`

# Deployment

A deployment script for Heroku is already setup in the `heroku-postbuild` script in `package.json`. The deploy with Heroku is very straightforward if you just follow their instruction.







