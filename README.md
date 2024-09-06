# maaadychatbot
- Link: https://demo2-kouki.azurewebsites.net/
- A menu-based or button-based chatbot is a type of chatbot that interacts with users through a structured menu system. Instead of engaging in free-form conversations like some other chatbots, a menu-based chatbot presents users with a predefined set of options or choices.

# Directory structure
- backend: Contains Python FastAPI backend code
- db: contains the dump of the database. you need to import this into your MySQL db by using MySQL workbench tool
- dialogflow_assets: this has training phrases etc. for our intents
- frontend: website code

Install these modules
======================

- pip install mysql-connector
- pip install "fastapi[all]"

OR just run pip install -r backend/requirements.txt to install both in one shot

To start fastapi backend server
================================
1. Go to backend directory in your command prompt
2. Run this command: uvicorn main:app --reload


ngrok for https tunneling
================================
1. To install ngrok, go to https://ngrok.com/download and install ngrok version that is suitable for your OS
2. Extract the zip file and place ngrok.exe in a folder.
3. Open windows command prompt, go to that folder and run this command: ngrok http 80000
4. ngrok can timeout. you need to restart the session if you see session expired message.
