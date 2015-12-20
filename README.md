# GCI_UserList_webapp

Setup instructions:

Download MongDB @ https://www.mongodb.org/
<br />Copy all files from bin folder in Mongodb to the bin folder in GCI_UserList_webapp
<br /> Open up Node.js commmand prompt, cd to main directory and install dependencies with "npm install"
<br />Create a "data" folder in main directory
<br />Open up another Node.js command prompt, and cd to bin folder, run "mongod --dbpath <path to data folder>"
<br />Use the first command prompt to run "npm start"
<br />Acccess the webapp at http://localhost:3000
