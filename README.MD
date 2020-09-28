# Reactivities

This app is a basic website to demonstrate the capabilities of a React 16.8.6 front end calling a .Net Core 3.0.0 web api with an underly database.

It is an Activities editor, to add, update and delete events. Users will eventually be able to sign up for activities, and IM each other. This is the sample app created during the Udemy course: Complete guide to building an app with .Net Core and React (https://www.udemy.com/course/complete-guide-to-building-an-app-with-net-core-and-react)

## Technology Demonstrated

    .Net Core 3.0.0 web api
        Entity Framework Code First
        SQL Lite (eventually Sql Azure)
        Database seeding
        Web Api

    React 16.8.6 front end
        Typescript
        React Hooks
        Semantic UI
        Material Icons
        Axios

## Needed software

To edit or run this project, you should install:

    .Net Core 3.0.0
    Your favorite code editor (I used VS Code)
    Node
    NPM
    In VS Code Terminal, you should change to the client-app directory and type this command:

    npm install

## VS Code Extensions

I had the following extensions installed in VS Code:

    Extension                   Publisher
    ==========                  =========
    C#                          Microsoft
    C# Extensions               JosKreativ
    ES7 React/Redux Snippets    dsznajder
    NuGet Package Manager       jmrog
    Prettier                    Prettier
    SQLite                      alexcvzz
    Bracket Pair Colorizer 2    CoenraadS
    Auto Close Tag              Jun Han
    Auto Rename Tag             Jun Han
    ES Lint                     Dirk Baeumer
    Material Icon Theme         Philipp Kief

# Running the code

## Web Api Server

Hit F5 in VS Code will start the web api project and load an empty web page (still working on resolving this oddity)

## React front end

Open a new Terminal window in VS Code, change to the client-app directory, and type this:

npm start

This will bring up another web page with the front end running
