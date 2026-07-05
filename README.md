# SY_Bicycle

A C# console application for managing bicycle shop inventory and sales. It lets shop staff track stock, record sales transactions, and view inventory status from a simple command-line interface.

## Features

- **Inventory management** — add, update, and remove bicycle stock records (model, brand, price, quantity)
- **Sales processing** — record customer purchases and automatically update stock levels
- **Stock lookup** — search and view current inventory by model, brand, or category
- **Sales/stock reporting** — view basic summaries of sales made and remaining stock
- **Data persistence** — inventory and sales data are saved between sessions

> Adjust the list above to match the exact features implemented in your codebase.

## Tech Stack

- **Language:** C#
- **Type:** Console application
- **Storage:**  SQL 


## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Sulaxshajini/SY_Bicycle.git
cd SY_Bicycle
```

### 2. Restore dependencies

```bash
dotnet restore
```

### 3. Build the project

```bash
dotnet build
```

### 4. Run the application

```bash
dotnet run
```

## Project Structure

```
SY_Bicycle/
├── Program.cs           # Application entry point
├── Models/               # Bicycle, Sale, and other data models
├── Services/             # Inventory and sales business logic
├── Data/                 # Data access / persistence layer
├── SY_Bicycle.csproj     # Project file and dependencies
└── README.md
```

> This structure is a best-guess template — update the folder/file names to match your actual solution layout.

## Usage

Once running, the console presents a menu-driven interface. A typical flow looks like:

```
=== SY Bicycle Shop ===
1. View Inventory
2. Add Bicycle
3. Record Sale
4. View Sales Report
5. Exit

Select an option:
```

Enter the number corresponding to the action you want to perform and follow the on-screen prompts.

## Sample Workflow

1. Select **Add Bicycle** to register new stock with model, brand, price, and quantity.
2. Select **Record Sale** to sell a bicycle — stock quantity is reduced automatically.
3. Select **View Inventory** at any time to check current stock levels.
4. Select **View Sales Report** to review recorded transactions.



## Author

**Sulaxshajini**
