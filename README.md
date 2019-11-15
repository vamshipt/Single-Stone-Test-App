# Single-Stone-Test-App

Instructions to run project
--> Download application zip file and unzip
--> The folder contains a solution file and two projects
        1.MVC WebApplication for Entry and list contacts
        2.WEBAPI application
--> Packages are not included in the zip file due to size
--> LiteDB is used as a database for this application, LietDB should be installed using Nuget packet Manager
--> Sample liteDB used for this application is available in Test folder, LiteDB path is configured in config file for WebApi application. It should be pointed to the location it is saved
--> Once the Solution is loaded, both the projects should be set as startup project in solution properties
--> Path for calling WEBAPI is configured in web.config file. The Port number should be changed based on WebApi application Port
--> A new contact can be added, view all contacts,edit and delete contact can be performed with this application
