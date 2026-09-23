# Expense Tracker

A simple desktop expense tracking app built with .NET MAUI Blazor Hybrid. Add your daily expenses, see the running total, and delete entries you no longer need. All data is stored locally on your computer.

## Features

- Add an expense with a title, amount and category
- Date is recorded automatically
- Total spent is shown at the top and updates instantly
- Delete any expense from the list
- Data is saved in a local SQLite database, so it is still there after closing and reopening the app

## Built With

- .NET 10 (.NET MAUI Blazor Hybrid)
- MudBlazor for the user interface
- SQLite (sqlite-net-pcl) for local storage

## Requirements

- Windows 10 or 11
- .NET 10 SDK with the MAUI workload installed
- WebView2 Runtime (already included with most Windows installations)

## How to Run

```
git clone https://github.com/aynaimran29-hub/ExpenseTracker.git
cd ExpenseTracker
dotnet run -f net10.0-windows10.0.19041.0
```

## Author

aynaimran29-hub
