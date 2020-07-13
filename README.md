# redditech-dotnetcore-template
A sample .NET Core solution template implementation inspired by the articles in the [Good learning links](#good-learning-links) below and adding some of my own preferences for Redditech projects.


## Solution and Project structure and folder usage
Taking a look at [ASP.Net Core Repos](https://github.com/aspnet/) helped digest the usage of each of these folders better, but below I put some quick annotations from the [Scott Allen talk](https://www.youtube.com/watch?v=qxb62AErRWw) on their opinionated usage.

- build - the compiled output when a build is run
- docs - any documentation about the project
- deploy - any deployment scripts (e.g. build-pipeline.yaml for Azure)
- samples - any sample code for how to implement the project
- scripts - any scripts used e.g. database migration scripts
- src - the source code for any project folders
- test - the unit tests
- tools - any inline tools used to develop the project

## Roadmap of items added and to add
| Task | Status | Date | Notes
|----|----|---|----
| Create project folders and structure | Done | 13 Jul 2020 | Mostly copied from Scott Allen video in links
| Add a Blazor WASM solution, rewire the solution file| Done | 13 Jul 2020
| Add build and deployment to azure website | TODO |
| Add a EF Core solution with a console app to run db migrations and a simple sample database for customer information | TODO | --

## Good learning links
| Topic 
|----|----
| [Localization and Globalization for Blazor](https://soluling.com/Help/Blazor/Index.htm) |  
[Opinionated Approach to ASP.NET Core" talk by Scott Allen Video](https://www.youtube.com/watch?v=qxb62AErRWw)
