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
13.for the UI building it is used syncfusion.EJ asp.NET core it has its own web page to check in the demo section as well as its own documentation it is necessary to download the NUget package
14. It is necessary to import "@addTagHelper *, Syncfusion.EJ2" so the UI component will be visible (paste in view imports)
15. then add the stylesheet above the css rules to prevent override existing rules.
16. Last is to install the scripts as indicated in the web page, do not include the calendar
17. go to textbox, and copy the script to add a new text box and change the ID and Title
18. the background colors were changed in the project root
19. Need to put the keys 
