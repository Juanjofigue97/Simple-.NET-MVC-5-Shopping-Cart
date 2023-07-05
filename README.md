# Simple .NET MVC5 Shopping Cart
An experimental online shopping cart project using C# .NET MVC5, MSSQL, HTML5, CSS3 and JavaScript

![alt tag](https://raw.githubusercontent.com/mrjcka/Simple-.NET-MVC-5-Shopping-Cart/master/demo.PNG)

## Installation

As mentioned, this is a experimental project and is not ready for production. Please use on your own risk.

**Required libraries**:

- .NET Identity

**Steps of installation**

- Import project into Visual Studio (or alternative IDE)
- Import and run SQL script attached name `Scripts.sql`. This will automatically generate database for the project.

## Features

- Frontend pages - display Products, Orders, Suppliers for Customers and Visitor.
- Authentication - a `Visitor` can become a `Customer`
- Admin Page
    - CRUD functions for Products and Suppliers, view Orders, view and delete Customer
    - Displaying Stock level using chartjs

## How to work with git

1. git checkout master
2. git pull
3. git checkout -b bug-ee-branch-name
4. git add .
5. git commit
6. git checkout master
7. git pull
8. git checkout bug-ee-branch-name
9. git merge master
10. git git checkout master
11. git merge bug-ee-branch-name
12. git pull
13. git push
14. git branch -d bug-ee-branch-name










