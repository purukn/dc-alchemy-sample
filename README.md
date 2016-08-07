# dc-alchemy-sample Overview

This Node.js Application demonstrates how Custom entities can be identified in a PDF document. PDF documents when uploaded gets converted into sections using Watson Document Conversion service. Alchemy Language's getEntities API is then used using a Custom trained model to get entities present in the sections of the PDF document.

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/purukn/dc-alchemy-sample)

## Run the app locally

1. [Install Node.js][]
2. Download and extract the starter code from the Bluemix UI
3. cd into the app directory
4. Run `npm install` to install the app's dependencies
5. Run `npm start` to start the app
6. Access the running app in a browser at http://localhost:6001

[Install Node.js]: https://nodejs.org/en/download/

## API information

URL: /entities (POST)
Input: PDF document uploaded as form-data parameter named "file"
