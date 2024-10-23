# MVC Application with MongoDB and Entity Framework Core

This project demonstrates how to set up and use MongoDB as the database provider in an ASP.NET Core MVC application with the help of Entity Framework Core (EF Core). By leveraging the MongoDB .NET driver, we combine the flexible schema of a NoSQL database with the familiar, object-oriented approach of EF Core.

## Key Features

- **MongoDB as Database Provider**: MongoDB is used as the database provider, connected through a configured connection string. This setup allows for flexible, document-based storage, which is ideal for applications needing a more schema-less database design.
  
- **EF Core Integration**: Although EF Core is designed primarily for relational databases, we’ve integrated it with MongoDB using the `MongoDB.Driver`. This allows developers to use EF Core's abstractions while benefiting from MongoDB’s scalability and flexibility.

- **CRUD Operations**: The application demonstrates standard Create, Read, Update, and Delete (CRUD) operations using MongoDB. These operations are managed within the MVC architecture and implemented in an EF Core-like manner for consistency.

- **Data Seeding**: The project includes logic to seed initial data into the MongoDB collections, ensuring that the application starts with some sample data.

## Getting Started

1. Clone the repository to your local machine.
2. Ensure that MongoDB is installed and running locally, or configure a remote MongoDB instance.
3. Update the MongoDB connection string in `appsettings.json` to match your database configuration.
4. Run the application using `dotnet run` or from Visual Studio.
5. Access the MVC views to perform CRUD operations on the MongoDB collections.

## Prerequisites

- [.NET 6 or later](https://dotnet.microsoft.com/download)
- [MongoDB Server](https://www.mongodb.com/try/download/community)
- MongoDB.Driver NuGet Package

## How to Use

Once the application is running, you can navigate through the provided MVC views to add, update, and delete data in the MongoDB collections. The application will automatically handle interactions with the database using MongoDB’s driver while maintaining an EF Core-like structure.
