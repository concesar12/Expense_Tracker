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
8. Start the migration to have a DB