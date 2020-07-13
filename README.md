# redditech-dotnetcore-template
A sample .NET Core solution template implementation inspired by (but not faithful to *all* of) the "Opinionated Approach to ASP.NET Core" talk by Scott AllenVideo link at
https://www.youtube.com/watch?v=qxb62AErRWw and adding some of my own preferences for Redditech projects.


## Solution and Project structure and folder usage
Taking a look at https://github.com/aspnet/ repos also helped digest the usage of each of these folders better, but below I put some quick annotations from the talk on their opinionated usage.

- build - the compiled output when a build is run
- docs - any documentation about the project
- deploy - any deployment scripts (e.g. build-pipeline.yaml for Azure)
- samples - any sample code for how to implement the project
- scripts - any scripts used e.g. database migration scripts
- src - the source code for any project folders
- test - the unit tests
- tools - any inline tools used to develop the project
