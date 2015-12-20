# GCI_UserList_webapp

Setup instructions:

Download MongDB @ https://www.mongodb.org/
Copy all files from bin folder in Mongodb to the bin folder in GCI_UserList_webapp
Open up Node.js commmand prompt, cd to main directory and install dependencies with "npm install"
Create a "data" folder in main directory
Open up another Node.js command prompt, and cd to bin folder, run "mongod --dbpath <path to data folder>"
Use the first command prompt to run "npm start"
Acccess the webapp at http://localhost:3000
