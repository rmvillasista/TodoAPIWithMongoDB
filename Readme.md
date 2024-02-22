### Initialize Project

Go to File > New > Project.

Select the ASP.NET Core Web API project type, and select Next.

Name the project BookStoreApi, and select Next.

Select the .NET 8.0 (Long Term support) framework and select Create.

In the Package Manager Console window, navigate to the project root. Run the following command to install the .NET driver for MongoDB:

```
Install-Package MongoDB.Driver
```

