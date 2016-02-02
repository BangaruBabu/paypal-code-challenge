-- Used NodeJS, Restify npm to expose REST APIs
-- Used mongoose as a ORM to communicate with MongoDB database
-- Used the proper HTTP verbs to make it RESTful (GET, POST and DELETE)
-- Return JSON data

 >> Prerequisites 

	1.Install NodeJS
		with dependencies
		"dependencies": {
		     "restify": "*",
			"mongoose":"*",
			"require":"*",
			"mongoose-schema-extend":"*",
		   "log4js":"*"
		}
	2.Install MongoDB ad create new "Bird" database with "birds" collection



open command propmt or terminal

1. run command use npm install to install all dependencies

2. $ node app.js

Server will start and listen on port 8080. 

 Tested all the APIs using REST Client plugin.

 While creating new bird record please mention "id:hardcodevalue" as follows.

 {
  "family" : "Samplefamily",
    "name" : "SampleBird",
    "id" : 1,
    "continents" : [ 
        "samplecontinentone", 
        "samplecontinenttwo", 
        "samplecontinentthree"
    ]

}



