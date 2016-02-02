# Paypal-Code-Challenge
Address Book Code - Code Challenge

Designed Two Independent Components Server and Client to project Cohesiveness 

# Server Component
-  Node and Restify
-  MongoDB & Mongoose ODM

# Client Components
- Angular
- Express JS
- HTML and BootStrap

# Steps to Run Server
- Clone GitHub Repository using URL https://github.com/BangaruBabu/paypal-code-challenge.git
- We will get two Directories Under Root Folder
  1) Client 2) Server Under 
- Access Server Folder from Command Prompt and run "node app" to run REST API
- This RESTFul API will run on 8080 port. 

Note:  
- DBUri has been targeted to DaaS SandBox Account (MongoLab) . We can change by locating server/Config/config.js file
- We can test server by accessing http://localhost:8080/api/v1/persons

# Steps to Run Client
- Open Client Directory 
- Access Client folder through command prompt and hit "node server" to run web client
- Note: If we change port in Server , please configure the same in Client/Controllers/controller.js as i have hard coded URL
- We can access by hitting http://localhost:8000 

#  Screenshot
![Image of Output ](https://github.com/BangaruBabu/paypal-code-challenge/blob/master/client/public/Screen-1.PNG)




