Firstly open Backend Folder and create .env file
\\content of .env file
PORT = 8080
CLIENT_ID=963430980453-n37upvkss6op7tmd2topmvrvr8nv8ub3.apps.googleusercontent.com
CLIENT_SECRET=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
CLIENT_URL=http://localhost:3000
HOST = HostName
DATABASENAME = DBNAME
USER = YOUR USERNAME
PASSWORD = YOUR PASSWORD

Secondly open Frontend Folder and create another .env file
\\content of .env file
REACT_APP_API_URL=http://localhost:8080
REACT_APP_NODE_ENV=development


After that open Terminal and split it
open one with frontend folder
gave command - npm ci
             - npm start
open another with backend folder
gave command - npm i
             - npm run dev
