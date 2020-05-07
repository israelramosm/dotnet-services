# Dotnet Rest Services

Simple dotnet webapi application using rest services.

TODO: Next thiadd jwt
[jwt tutorial that I found on internet](https://jasonwatmore.com/post/2019/10/11/aspnet-core-3-jwt-authentication-tutorial-with-example-api)

## Starting

link: <https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-3.1&tabs=visual-studio-code>

```shell
dotnet new webapi -o TodoApi
cd TodoApi
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.InMemory
code -r ../TodoApi
```

## Run the App

### Install C# extensions

- C# extension : Microsoft

Press Ctrl+F5 to run the app.
In a browser, go to following URL: <https://localhost:5001/api/WeatherForecast>

## Dot NET Core CLI

CLI to create controller and more.

```shell
dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet tool install --global dotnet-aspnet-codegenerator
dotnet aspnet-codegenerator controller -name TodoItemsController -async -api -m TodoItem -dc TodoContext -outDir Controllers
```

## JWT tutorial

Look into [this tutorial](https://jasonwatmore.com/post/2019/10/11/aspnet-core-3-jwt-authentication-tutorial-with-example-api)
