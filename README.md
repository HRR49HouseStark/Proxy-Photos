# FEC Proxy Server Template
Project deployment URL: http://54.177.124.31:3000/

## Overview
This proxy server displays all four project members' services on a single page and permits communication with their corresponding API's. It uses middleware to serve up static asset requests, proxy requests for individual client app bundles, and proxy requests from running client apps to their respective services.

## Instructions
- Run `nvm use 14` to switch the version of node required for this project. If this version isn't currently installed, run `nvm install` to install this version
- Run `npm install` to install all the project dependencies
- Read the information and instructions in `server/config/services.js` to provide the required configuration information to enable the proxying functionality
- Run `npm start` or `npm start:dev` to start the server