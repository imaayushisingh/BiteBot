# BiteBot
End to end Chatbot project --> frontend using html and css, backend using python and fastapi, chatbot using dialogflow which uses concepts of NLP, all of this interacts with MySQL database

## Directory structure
===================
Backend: Contains Python FastAPI backend code
Dtabase: contains the dump of the database. you need to import this into your MySQL db by using MySQL workbench tool
Frontend: website code

## Install these modules
======================
pip install mysql-connector
pip install "fastapi[all]"

## To start fastapi backend server
================================
1. Go to backend directory in your command prompt
2. Run this command: uvicorn main:app --reload

## ngrok for https tunneling
================================
1. To install ngrok, go to https://ngrok.com/download and install ngrok version that is suitable for your OS
2. Extract the zip file and place ngrok.exe in a folder.
3. Open windows command prompt, go to that folder and run this command: ngrok http 8000

NOTE: ngrok can timeout. you need to restart the session if you see session expired message.

