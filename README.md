# Assignment-VitalHub


* There are 3 projects included in one solution. extarct zip file
* Solution file included in ChineseDragonApp

Steps to create relevant DB and run the application
1. Run the create script 'CreateScript_ChineseDragon' - Include all table creation ad test data set)
2. Run the create script 'CreateStoredProc_ChineseDragon' - Includes all the stored procedures needed 
3. Set the WebAPI appsettings.json 'MySettings.DbConn' value to database connection string
4. Set the ChineseDragonApp appsettings.json 'MySettings.Baseurl' value to web api base url
5. Set the Ordering app index.html page form action value to web api base url + '/CreateOrder'
	Eg: https://localhost:44377/api/Resturent/CreateOrder
