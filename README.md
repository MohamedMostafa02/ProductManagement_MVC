# Product Management MVC - ASP.NET Core

This is a simple product management project built with ASP.NET Core MVC. It demonstrates the basics of MVC (Model - View - Controller) with Services and Dependency Injection.

Features:
- Display a list of all products.
- View details of a single product by ID.
- Uses an In-Memory List instead of a database for testing.
- Views designed with Razor.
- Dependency Injection for service management.

How It Works:
- Model (Product.cs): Represents a product with properties like Id, Name, Price, Category, etc.
- Service (IProductService & ProductService): IProductService defines the main methods (GetAllProducts, GetProductById). ProductService implements the interface using an in-memory list of products.
- Controller (ProductController): Handles user requests, calls services, and returns Views with data.
- Views: Index.cshtml shows a table of all products. Details.cshtml shows details of a selected product.

Example Output:
- Product Catalog (Index): Table with product image, name, category, price, stock, created date, and a button to view details.
- Product Details (Details): Page with a larger product image, name, description, price, stock status, and created date.

How to Run:
1. Open the project in Visual Studio 2022 or any IDE supporting ASP.NET Core.
2. Ensure .NET 8 SDK is installed.
3. Run from terminal with: dotnet run
4. Open browser at: https://localhost:5001 or http://localhost:5000

Requirements:
- .NET 8 SDK
- Visual Studio 2022 / Rider / VS Code
- Modern browser (Chrome, Edge, Firefox)

Author:
Mohamed Mostafa (mo@gmail.com)

