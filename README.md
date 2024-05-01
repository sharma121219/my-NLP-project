# End-to-End NLP Project | Build a Chatbot in Dialogflow | NLP 
I build a chatbot in Dialogflow for a food delivery system. It will be an end-to-end project covering Dialogflow basics, building a backend in python and Fastapi, interactions with MySQL database, and much more. We will cover Dialogflow fundamentals such as intents, entities, contexts, etc.
Directory structure
===================
backend: Contains Python FastAPI backend code
db: contains the dump of the database. you need to import this into your MySQL db by using MySQL workbench tool
dialogflow_assets: this has training phrases etc. for our intents
frontend: website code

Install these modules
======================

pip install mysql-connector
pip install "fastapi[all]"

OR just run pip install -r backend/requirements.txt to install both in one shot

To start fastapi backend server
================================
1. Go to backend directory in your command prompt
2. Run this command: uvicorn main:app --reload

ngrok for https tunneling
================================
1. To install ngrok, go to ngrok version that is suitable for your OS
2. Extract the zip file and place ngrok.exe in a folder.
3. Open windows command prompt, go to that folder and run this command: ngrok http 80000

NOTE: ngrok can timeout. you need to restart the session if you see session expired message.
body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

header {
    background-color: #ff5733;
    text-align: center;
    padding: 20px;
    color: #fff;
}

h1 {
    margin: 0;
    padding: 0;
}

nav a {
    margin: 0 10px;
    text-decoration: none;
    color: #fff;
    transition: color 0.3s ease-in-out;
}

nav a:hover {
    color: #f0f0f0;
}

section {
    margin: 20px;
    background-color: #fff;
    border-radius: 8px;
    padding: 20px;
    box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.1);
}

section h2 {
    color: #ff5733;
}

footer {
    background-color: #ff5733;
    text-align: center;
    padding: 10px;
    color: #fff;
    position: fixed;
    bottom: 0;
    width: 100%;
}

.chat-bot {
    position: fixed;
    right: 20px;
    bottom: 20px;
    border: none;
    z-index: 1000; 
}
.container {
    margin: 0 auto;
    max-width: 1200px; /* or any other value */
    padding: 0 20px; /* adding 20px of padding */
}

body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
    text-align: center;
}
section img {
    display: block;
    margin: auto;
    width: 100%;
    height: auto;
}
body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

header {
    background-color: #ff5733;
    text-align: center;
    padding: 20px;
    color: #fff;
}

h1 {
    margin: 0;
    padding: 0;
}

nav a {
    margin: 0 10px;
    text-decoration: none;
    color: #fff;
    transition: color 0.3s ease-in-out;
}

nav a:hover {
    color: #f0f0f0;
}

section {
    margin: 20px;
    background-color: #fff;
    border-radius: 8px;
    padding: 20px;
    box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.1);
}

section h2 {
    color: #ff5733;
}

footer {
    background-color: #ff5733;
    text-align: center;
    padding: 10px;
    color: #fff;
    position: fixed;
    bottom: 0;
    width: 100%;
}

.chat-bot {
    position: fixed;
    right: 20px;
    bottom: 20px;
    border: none;
    z-index: 1000; 
}
.container {
    margin: 0 auto;
    max-width: 1200px; /* or any other value */
    padding: 0 20px; /* adding 20px of padding */
}

body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
    text-align: center;
}
section img {
    display: block;
    margin: auto;
    width: 100%;
    height: auto;
}
HOW TO USE CODE......
![banner](https://github.com/sharma121219/my-NLP-project/assets/139925541/088550e1-60e1-4907-b827-d794fccbf7b5)
![menu1](https://github.com/sharma121219/my-NLP-project/assets/139925541/717cd02b-3dd5-470b-9cc5-e9d72cbc541a)
![menu2](https://github.com/sharma121219/my-NLP-project/assets/139925541/3962775d-9672-4662-9c84-1ca2b43b3148)
![menu3](https://github.com/sharma121219/my-NLP-project/assets/139925541/a66db36b-d991-4ea8-879d-351a16c7a19f)


































