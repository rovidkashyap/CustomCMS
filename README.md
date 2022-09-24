# CustomCMS

Usage of the Project - Download of Clone the Application in Visual Studio 2019 or 2022 and go to appsettings.json and change the connection string as per your system. Now go to Visual Studio -> Tools -> NuGet Package Manager -> Package Manager Console and then type Command [Update-database]. 
This is run the Migrations and seed the database so when you run the application database will be created by application.

This is Custom CMS Application Design in .Net Core 3.1, MVC Core, Entity Framework Core, Identity 2.2., Microsfot SQL Server. In this application we are going to use the Repository Pattern for accessing data through several Layers includes Dependency Injection and also having Unit Of Work. For Authentication and authorization we are going to use the Asp.net Identity 2.2 in the application.

Here are the Projects Library Details for the Application :-

1 - BulkyBook.Models - This Layer is created in .Net Core 3.1 Class Library which includes Entity Types and View Models for Application

2 - BulkyBool.DataAccess - This Layer is created in .Net Core 3.1 CLass Library which consists of Repository Class (i.e Interface and Classes), Data Context for the Application, having data for seed which includes in DbInitializer and also contains Database Migration.

3 - BulkyBook.Utility - This is another layer created in .Net Core 3.1 Class Library having all the Utility classes whcih includes Email Sending Options, Braintree Plugin settings, and several other settings

4 - BulkyBook - This is our main Layer which design in .Net Core MVC Application which consists our User Interface and having Razor Page for View.

Default Login Details - 
username - admin@gmail.com 
password - Admin123*
