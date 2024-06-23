# Library Management System

This is a Library Management system where the librarian can manage the books ,
members and with a basic dashboard view.The member can login with their credentials and
view the books along with their membership status.The web application is developed using
Asp.net core mvc using Microsoft entityframeworkcore.The user data is stored by extending
the Asp.net core identity system ,along with the user authentication.Roles related to the users are managed using identity tables.The books are stored using a custom table.


## Technologies
Frotend : HTML , CSS , Bootstrap,Javascript\
Backend : ASP.Net Core(MVC) 6\
Server  : MS Sql Server
## Project Setup
- Unzip the file 
- Open the the file with .sln extension
- Inside the visual studio ,open the appsettings.json file
    - Insert your server and database name 
    "Server={Your server};Database={Your database};Integrated   Security=True;TrustServerCertificate=True;"
- Open package manager console and execute the command
    - pm> update-database
- Build and run the project
- Login the application using the credentials in the ApplicationDbContext


## Challenges
Extending the Asp.net identity system was challenging , but through my research ,I was able to overcome those Challenges.
## Pending Task
None
