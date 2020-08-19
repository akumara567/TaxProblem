# Assumption:

1 - Taxes may change at any time, so i have made the applicaiton in such a way that, taxes can be configured in DB and can change anytime, with out the deployment
	we can get the updated taxes any time from the DB, hence used this approach
2 - Since we made this app to accept dynamic tax changes, we may sell this kind of application to other muncipal corporations
3 - Hence I used microservice architecture, easy to expose the functionalities through endpoints and independent services can be exposed
	
#Tools and Libraries used

- Entity Framework Core
- CsvHelper
- ASP.NET Core WebAPI
- Sqlite

# How to run

```
$dotnet run -p webapi
```

PS: Since i dont have the latest version of dotnet in my machine, i have used ASP.NET Core beta version
