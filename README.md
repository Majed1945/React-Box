# Box 📦 

<img src="https://media.giphy.com/media/4YIdN9xbtuz46cFnIN/giphy.gif" width="500" hieght="100%">

Box is a Full-stack web application for a package delivery service that allows shipping companies to track shipments and users to send/receive shipments. 
The system functions similar to other package delivery companies (e.g., SMSA, DHL or FedEX). 
The application also keeps track of customers (who ship packages) and customers (who receive packages)
The detailed information of company employees and customers is maintained in the database and can be accessed/viewed in the administrator page.

# Project Set Up
1-clone the repository<br>
2-npm install for the root folder and for the frontend folder<br>
3-at the root folder, run "npm run server", then run "npm run client"<br>
4-add the .env file which has the following content:<br>
MONGO_URI = "mongodb+srv://Majd:3090Mm5.@cluster0.nlub8pr.mongodb.net/Box"
JWT_SECRET = koi123<br>
5-At first trial, please go to the route "/register" because the application requires registration to create local storage that is necessary to run the main page
