# Notepad app

A Repo to demonstrate how to make a Notepad REST-API/App that allows to List, Add, Edit and delete Notes.

- backend REST-API using Node, Express and MongoDB
- frontend React and Node

# The look of the app:

![app](https://raw.githubusercontent.com/fgl27/Notepad_app/master/app/public/Screenshot_from_2021-08-05_15-08-35.png)


# Starting REST-API and APP

### mongoDB server

``` bash
# Starting mongoDB (linux Ubuntu)
sudo apt-get install mongodb

# Starting mongoDB
mongo

# View the notes object
use notes
db.notes.find().pretty();

```

### Express API

``` bash
# Navigate to folder api
cd api

# Install dependencies
npm install

# Starting Express
npm start

```

### React APP

``` bash
# Navigate to app folder
cd app

# Install dependencies
npm install

# Start the app
npm start

```

**The Express Server starts at the link http://localhost:5000 and the app http://localhost:3000**
