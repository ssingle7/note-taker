# note-taker
The purpose of this note taking application is to allow the user to write, save, and delete notes. For users that need to keep track of a lot of information, it's easy to forget or be unable to recall something important. Being able to take persistent notes allows users to have written information available when needed.

* HTML routes were created to get and return information from one html file to the other.

* This application used a `db.json` file on the backend that is used to store and retrieve notes using the `fs` module.

* API routes were created to: read the `db.json` file and return all saved notes as JSON 

  * read the `db.json` file and return all saved notes as JSON.

  * to receive a new note to save on the request body, and then return the new note to the client.

  * to receive a query parameter containing the id of a note to delete. 
  

 # Installation

Clone the repository to your local development environment. 

Run npm install to install all dependencies. To use the application locally, run node server.js in your CLI, and then open http://localhost:3000 in your preferred browser. The Note Taker app is also live on Heroku for use.

## Preview 

![note taker](/note taker.PNG)

![NoteTaker](./Note Taker.gif)


## Deployed Link



### Credits

* 02-ask-the-class

* Tutor

* Ask BCS 

### License 

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

Copyright (c) [2020] [Selena Singleton]

