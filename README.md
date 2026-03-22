Product Inventory Management API: 

A basic ASP.NET Core Web API project for managing product inventory using **Entity Framework Core** and SQL Server.

Features: 

*   CRUD operations for Products
*   SQL Server integration
*   Swagger for API testing
*   Validation & basic error handling

Tech Used:

*   ASP.NET Core Web API
*   Entity Framework Core
*   SQL Server

How to Run:

1.  Clone the repo
        git clone https://github.com/Lokiran/Product_Inventory_Management.git
2.  Update **appsettings.json** with your SQL Server connection string
3.  Run migrations:
        dotnet ef database update
4.  Start the API:
        dotnet run
5.  Test using Swagger at:
        https://localhost:<port>/swagger

Endpoints: 

*   GET all products
*   GET product by ID
*   POST create product
*   PUT update product
*   DELETE remove product

Folder Structure: 

    Controllers/
    Models/
    Data/
    Program.cs
    appsettings.json

Conclusion: 

This project demonstrates a basic yet functional Product Inventory Management API built using ASP.NET Core and SQL Server. It covers essential concepts like CRUD operations, EF Core integration, validation, and API testing with Swagger. It provides a solid foundation for learning and can be extended with additional features as needed.
