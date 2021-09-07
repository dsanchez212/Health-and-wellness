# Health and Wellness

---

## Table of Contents

- [Description](#description)
- [How To Use](#how-to-use)

---

## Description

Full-stack application that allows users to create an account, manage health reminders, and use weight tracking features. 

#### Technologies

- MongoDB
- Express.js
- Node.js
- React.js

[Back To The Top](#health-and-wellness)

---

## How To Use

### Installation

#### Things you should already have installed:
- yarn
- nodejs
- nodemon
- localhost MongoDB connection (assuming default port is 27017)


#### Things to setup in the local mongodb database:

Do the following shell commands:

> use health_wellness

> db.createCollection("alarms")

> db.createCollection("counters")

> db.createCollection("items")

> db.createCollection("users")

> db.createCollection("weights")

#### Starting Application Locally:

Open two terminals:

- Terminal 1: navigate to root project directory
- Terminal 2: navigate to frontend directory

> Terminal 1: yarn

> Terminal 2: yarn

> Terminal 1: sudo npm start

> Terminal 2: sudo npm start







