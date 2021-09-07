<h2>Steps on setting up the application</h2>

<h3>Things you should already have installed:</h3>
<ul>
    <li>yarn</li>
    <li>nodejs</li>
    <li>nodemon</li>
    <li>localhost MongoDB connection (assuming default port of 27017)</li>
</ul>

</br>

<h3>Things to setup in the local mongodb database:</h3>

Do the following shell commands:</br>


use health_wellness</br>

db.createCollection("alarms")</br>

db.createCollection("counters")</br>

db.createCollection("items")</br>

db.createCollection("users")</br>

db.createCollection("weights")</br>


</br>

<h3>Starting Local Testing:</h3>

<please note> Open two terminals:</br>

<i>Terminal 1</i>: navigate to root project directory</br>

<i>Terminal 2</i>: navigate to frontend directory</br>


<i>Terminal 1</i>: yarn</br>

<i>Terminal 2</i>: yarn</br>

<i>Terminal 1</i>: sudo npm start</br>

<i>Terminal 2</i>: sudo npm start</br>
