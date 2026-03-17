This project is a web-based Expense Tracker application built using ASP.NET Core MVC. The application allows users to record, manage, and visualize their daily expenses through a clean dashboard interface.

The system provides functionality for managing categories and transactions, along with visual insights using charts and widgets. It demonstrates how to build an enterprise-style ASP.NET Core MVC application using modern UI components and structured MVC architecture.

The application was developed as a learning project to understand ASP.NET Core MVC, Entity Framework Core, CRUD operations, and dashboard visualization techniques.

Features
1. Category Management

Users can manage expense categories.

Create new categories

Edit existing categories

Delete categories

View categories in a grid with sorting and paging

Examples of categories:

Food

Transportation

Bills

Entertainment

2. Transaction Management

Users can manage individual expense transactions.

Each transaction contains:

Amount

Category

Note / Description

Date

Functions include:

Add transaction

Edit transaction

Delete transaction

View transaction history

3. Dashboard

The dashboard provides a quick financial overview.

Features include:

Total income vs expenses

Monthly expense chart

Recent transactions

Visual summary using charts

4. Data Visualization

Charts are used to display expense patterns and trends.

Examples:

Monthly expense chart

Category-based spending distribution

These help users quickly understand their spending habits.

Technologies Used
Backend

ASP.NET Core MVC

C#

Entity Framework Core

Frontend

Razor Views

SyncFusion UI Components

Bootstrap

Database

SQL Server

Development Tools

Visual Studio

.NET Core SDK

Project Architecture

The application follows the MVC (Model-View-Controller) design pattern.

Models

Represent database entities.

Examples:

Category

Transaction

Controllers

Handle application logic and requests.

Examples:

CategoryController

TransactionController

DashboardController

Views

Responsible for UI rendering using Razor syntax.

Examples:

Category CRUD views

Transaction views

Dashboard page
