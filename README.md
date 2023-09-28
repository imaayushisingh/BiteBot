# BiteBot
This is an end-to-end chatbot project that combines various technologies to create a functional chatbot. The project includes:
- Frontend: Developed using HTML and CSS.
- Backend: Powered by Python and FastAPI.
- Chatbot: Created using Google Dialogflow, utilizing Natural Language Processing (NLP) concepts.
- Database: Interaction with a MySQL database.

## Directory structure
- Backend: Contains Python FastAPI backend code
- Database: contains the dump of the database. you need to import this into your MySQL db by using MySQL workbench tool
- Frontend: website code

## Install these modules
- mysql-connector:
  ```bash
  pip install mysql-connector
  ```
- FastAPI:
  ```bash
  pip install fastapi[all]
  ```

## To start fastapi backend server
- Go to backend directory in your command prompt
- Run this command:
  ```bash
  uvicorn main:app --reload
  ```

## ngrok for https tunneling
- To install ngrok, go to https://ngrok.com/download and install ngrok version that is suitable for your OS
- Extract the zip file and place ngrok.exe in a folder.
- Open windows command prompt, go to that folder and run this command:
  ```bash
  ngrok http 8000
  ```

### NOTE: ngrok can timeout. you need to restart the session if you see session expired message.

