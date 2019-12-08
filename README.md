# Dotnet Rest Services
Simple dotnet webapi application using rest services.

## Starting
link: https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-3.1&tabs=visual-studio-code

```shell
dotnet new webapi -o TodoApi
cd TodoApi
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.InMemory
code -r ../TodoApi
```

## Run the App

Press Ctrl+F5 to run the app. 
In a browser, go to following URL: https://localhost:5001/WeatherForecast.