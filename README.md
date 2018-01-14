# nivo.node.memkeep

A litte gadget to easily search for your notes that are suppossed to be managed in a google spreadsheet.

## Installation

`npm install`

download the latest [nwjs](https://nwjs.io/) sdk

## Creating a service-account 

You must create a service-account to share your spreadsheets with so this app will be capable of reading your the spreadsheets while they are still not public to the web.

Once you have successfully created a [service account](https://www.google.de/search?q=google+create+service+account) you can download a json file (creds.json) containing the credentials for that service account. Once you placed a copy into the app folder you are ready to build and run the application.

## Build and Run

Hit the run.bat or run.sh to build a debug version

## Notes

The reason why the whole logic is in a single file is that this is just a comfortable way for me to develop this application on an ipad while I am on may way to work. As this app scales I will seperate the whole logic into way smaller pieces.