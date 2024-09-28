# Project Documentation

## Create a new EC2 Instance for the MERN stack project and start the instance on AWS

![Screenshot 149](<img/Screenshot (221).png>)

## Login to the server on Windows Terminal

![Screenshot 149](<img/Screenshot (222).png>)

## Update server components (sudo apt update)

![Screenshot 149](<img/Screenshot (223).png>)

## Download node

- Node dowloading

![Screenshot 149](<img/Screenshot (224).png>)

- Node download concluded

![Screenshot 149](<img/Screenshot (225).png>)

## Install nodejs

![Screenshot 149](<img/Screenshot (226).png>)

## Check to be certain nodejs had been installed

## Check to be certain node package manager (npm) has been installed

## Create Todo directory and 'cd' into it

![Screenshot 149](<img/Screenshot (228).png>)

## Create a node project using 'npm init'

![Screenshot 149](<img/Screenshot (230).png>)

## Install expressjs

![Screenshot 149](<img/Screenshot (231).png>)

## Create index.js file

![Screenshot 149](<img/Screenshot (232).png>)

## Contents of index.js file

![Screenshot 149](<img/Screenshot (233).png>)

## Run index.js using node (server should be running)

![Screenshot 149](<img/Screenshot (234).png>)

## Edit EC2 Instance inbound rules

- Open TCP port 5000 and Allow request from anywhere to connect

![Screenshot 149](<img/Screenshot (235).png>)

## Acess server IP address from a browser and get a welcome response

![Screenshot 149](<img/Screenshot (236).png>)

## Create 'routes' directory and 'cd' into it

## Create file api.js

![Screenshot 149](<img/Screenshot (237).png>)

## Contents of api.js file

![Screenshot 149](<img/Screenshot (238).png>)

## Back to home, install mongoose

![Screenshot 149](<img/Screenshot (239).png>)

## Create models directory and 'cd' into it

## Create todo.js file and open it using vi editor

![Screenshot 149](<img/Screenshot (240).png>)

## Contents of todo.js file

![Screenshot 149](<img/Screenshot (241).png>)

## Get back inside the routes directly and edit the api.js file

![Screenshot 149](<img/Screenshot (242).png>)

## Edit to the api.js file

![Screenshot 149](<img/Screenshot (243).png>)

## Create a Cluster on mongodb.com

![Screenshot 149](<img/Screenshot (249).png>)

## 'cd' into Todo directory and create .env file

![Screenshot 149](<img/Screenshot (250).png>)

## Content of .env file - contains the connect string to the mongo database created on mongodb.com

![Screenshot 149](<img/Screenshot (251).png>)

## Now edit index.js to connect to the created database

![Screenshot 149](<img/Screenshot (252).png>)

## New contents of index.js file

![Screenshot 149](<img/Screenshot (253).png>)

## Cluster on mongodb, other network access parameters configured

![Screenshot 149](<img/Screenshot (269).png>)

## Create a POST request to /api/todos on Postman

## Edit the Headers section to include the 'Content-Type' header with the value 'application/json'

![Screenshot 149](<img/Screenshot (270).png>)

## Edit the Body section to include to todo to post

![Screenshot 149](<img/Screenshot (271).png>)

## In the Todo diretory, create a react app

![Screenshot 149](<img/Screenshot (272).png>)

## Install 'concurrently' as a dependency

## Install 'nodemon' as a dependency

![Screenshot 149](<img/Screenshot (273).png>)

## Open pacakge.json and made edits to the script key

- Script to include 'nodemon' and 'concurrently' workiing at the start of the server app

![Screenshot 149](<img/Screenshot (275).png>)
