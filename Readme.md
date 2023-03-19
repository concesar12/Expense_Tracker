ASP in .net core 6 project

Steps

1. Create the project
2. Download necesary tools :

- Entityframework core, Tools, sql server

3. Build the models/ categories / Transaction
4. Create the foreign and primary keys between them
5. Create the db context
6. Add the db context to the main, or program file, in this case was used dependency injection (DI)
7. Populate the appsettings.json to set up server and DB name connectionstring
8. Start the migration to have a DB and build the project
9. open Package mnanager console and type "Add-Migration "Initial Create"" then Update-Database (Have SSMS and sql server express installed and configured)
10. then add the controller by going to controllers folder and then select Category and appcontext, then renaming the application controller (IMPORTANT-- it is mandatory to have all packages with the same version)
    12.It is ok to run right now
    13.for the UI building it is used syncfusion.EJ asp.NET core it has its own web page to check in the demo section as well as its own documentation it is necessary to download the NUget package
11. It is necessary to import "@addTagHelper \*, Syncfusion.EJ2" so the UI component will be visible (paste in view imports)
12. then add the stylesheet above the css rules to prevent override existing rules.
13. Last is to install the scripts as indicated in the web page, do not include the calendar
14. go to textbox, and copy the script to add a new text box and change the ID and Title
15. the background colors were changed in the project root
16. Need to put the keys
17. Add and create were merged into one making the new view category AddOrEdit
18. There was hidden value to be passed category ID added to AddOrEdit
19. Then button is going to be added too.
20. then add the buttons and align the html and css
21. things like button and font awesome were added to the index and site cshtml
22. Then change the previuos table in index for the grid in syncfusion
23. It was merged into one icon and category
24. create if for type in case is expense or income
25. Iclude ordering columns and paging to index.cshtml
26. Then is time to work for the last operation, delete in the category controller
27. Delete and details were delete since they don't have a real use in the app
28. Fav icon added to the page
29. Name on tab was added too
30. Add the categories view and the breadcrumbs  
31. Added new navigation buttons and style in titles
32. In order to have controllers working a good idea is to remove three dependencies(entityframework, sqlentity and tools) then install the latest version of entity framework, try to create the controller and finally install version 6 again.
33. Start with the transaction Controller
34. Do not forget to pass a freash instance of the view, in this case (new Transaction) into the controller 
35. Creating the view cshtml to make it look good
36. Passing the categories list to a variable
37. Implement the same add or edit and delete for the transactions
38. Add the validation (Server side)
39. Create the dashboard controller 
40. reserve space for the side bar

