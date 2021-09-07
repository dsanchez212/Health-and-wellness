Steps on setting up the application.

Things you should already have installed:
- yarn
- nodejs
- nodemon
- localhost MongoDB connection (assuming default port of 27017)

=============================================
Things to setup in the local mongodb database
=============================================
Do the following shell commands:

> use health_wellness

> db.createCollection("alarms")

> db.createCollection("counters")

> db.createCollection("items")

> db.createCollection("users")

> db.createCollection("weights")


=======================
Starting Local Testing!
=======================

<please note> open two terminals!

    <terminal one> navigate to root project directory

    <terminal two> navigate to frontend directory


<terminal one cmd> yarn

<terminal two cmd> yarn

<terminal one cmd> sudo npm start

<terminal two cmd> sudo npm start
