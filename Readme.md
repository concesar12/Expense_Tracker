ASP in .net core 6 project

Steps
1. Create the project
2. Download necesary tools : 
* Entityframework core, Tools, sql server
3. Build the models/ categories / Transaction
4. Create the foreign and primary keys between them
5. Create the db context
6. Add the db context to the main, or program file, in this case was used dependency injection (DI)
7. Populate the appsettings.json to set up server and DB name connectionstring
8. Start the migration to have a DB and build the project
9. open Package mnanager console and type "Add-Migration "Initial Create"" then Update-Database (Have SSMS and sql server express installed and configured)
11. then add the controller by going to controllers folder and then select Category and appcontext, then renaming the application controller (IMPORTANT-- it is mandatory to have all packages with the same version)
12.It is ok to run right now
