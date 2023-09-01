# Tiger Bank
Bank console app created with C#, Spectre.Console, Dapper, PostgreSQL and DbGate.


## General Info
<img align="right" src="https://i.imgur.com/a8l79xc.png" alt="image of main menu" width="600"/>
 
* [Styling](#styling)  
* [Class Structure](#class-structure) 
* [Database](#database)
* [UI](#ui)
* [App](#app)
* [Flowchart](#flowchart)
* [UML Diagram](#uml-diagram)
* [Trello Board](#trello-board)
* [Documentation](#documentation)






### Styling

This project utilizes Spectre.Console.

It is an open-source .NET library that makes it easier to create beautiful console applications.

### Class Structure

Classes are arranged in two separate folders:

* "Classes" folder contains classes used for communicating with the PostgreSQL database.

* "UI" folder contains classes used for the application interface.

### Database

The "Data" folder contains a class that connects to the PostgreSQL database with the help of Dapper.

The connection string is then used throughout our source code for sending and reveiving SQL queries.

We managed our database through DbGate.

### UI

The "UI" folder contains the menus shown in the console app, login logic as well as the main function that runs the app.

### App

From here the main run function is called to run the application.

### UML Diagram

* [Link to Google Drive](https://drive.google.com/file/d/1vQCeu-K2J1Fc-qbsBWSIx2MGAxsK7aLp/view)

### Trello Board

We used Trello as our platform to work with both Scrum and Kanban methods in this project.

* [Link to Trello](https://trello.com/b/JPEY79RS/grupp-tiger)
