# Google Sheets as a Database

Use Google Sheets as a primary database for your Next.js project. 

Watch on YouTube or follow allong with the full [Google Sheets Database Tutorial](https://fireship.io/lessons/google-sheets-database-nextjs/) 
## Install
``
yarn install
yarn dev
``

## Process
* Create a Spreadsheet
* Create a Next.js App
* Enable the Google Sheets API
* Get a Service Account Key
easy way : find account 'App Engine default service account'
* Save the Key
Generate key to the account and you can get some_key.json file.
Move it to your project and make .env.local file
```
GOOGLE_APPLICATION_CREDENTIALS=./secrets.json
SHEET_ID="Sheet ID found on Google Sheets URL"
```
* Authenticate the API
-> Share your sheet to ${YOUR_ID}@appspot.gserviceaccount.com
* run