# React Express Airbnb Template
A starter kit for building React-Express Applications. Devdependencies utilize Airbnb style configuration and integrate prettier plugin from VSCode.

# Usage

1. `npm i -g nodemon` (an utility that monitor for any changes in your source and automatically restarter your server)
2. `npm i && cd client && npm i` (install the dependencies and devdependencies)
3. Install prettier and eslint plugin in VSCode extension.
4. `npm run test` to run the Express server and serve your React front-end. The server is running on `localhost:8080` and the proxy is set to the same address in `/client/package.json`

# Deployment

A deployment script for Heroku is already setup in the `heroku-postbuild` script in `package.json`. You should be good to deploy by following their tutorial.

https://www.heroku.com/

