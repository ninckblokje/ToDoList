# ToDoList

Build Microsoft's my first Blazor app. A WebAssembly app with three functionalities:

1. Counter
1. Fetch data
1. ToDo list

See: <https://docs.microsoft.com/en-us/aspnet/core/tutorials/build-your-first-blazor-app?view=aspnetcore-3.1>

## Setup

Requirements:

- [Visual Studio Code](https://code.visualstudio.com/)
- [.NET Core SDK 3.1](https://dotnet.microsoft.com/download)

Setup Visual Studio Code using this link: <https://docs.microsoft.com/en-us/aspnet/core/blazor/get-started?view=aspnetcore-3.1&tabs=visual-studio-code>

Alternatively there is a devcontainer available for Visual Studio Code.

## Build

````
dotnet restore
dotnet build
````

## Run locally

````
dotnet run --pathbase=/ToDoList
````

## Publish

````
dotnet publish
````

The folder `bin/Debug/netstandard2.1/publish/` contains the artifacts which can be hosted on any webserver, but should respect the context path `/ToDoList/` (see [index.html](wwwroot/index.html)).
