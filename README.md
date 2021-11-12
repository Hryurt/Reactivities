# Reactivities

It is a project for training .NET 5 and React by using CQRS and Mediator patterns. Creating the CRUD application by .NET 5 is designed according to clean architecture. Therefore the solution file has four projects such as API, Application, Domain, and Persistence. For the React side, the TypeScript language and template are used. On the client-side approach, different libraries are utilized. MobX is used for statement managing, Axios is used for HTTPS requests, and React Router is used for routing. To design the user interface Semantic UI is selected.

The general theme of the project is activities. A user can monitor, create, edit, and delete activity. 

## Before Running

Before installing this program, follow the instructions below. (If you have already installed these requirements, disregard this part.)
* Install .NET SDK 5.0+ [here](https://dotnet.microsoft.com/download/dotnet/5.0)
* Install Node.js [here](https://nodejs.org/en/)
* Install EF Core by using the command below.
```
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
```

## How To Run

* Use the dotnet restore command for package management main folder.
```
dotnet restore
```
* Use the npm install command for module management in the client-app folder.
```
npm install
```
* Start .NET with the command below in the API folder.
```
dotnet watch run
```
* Start React with the command below in the client-app folder.
```
npm start
```
