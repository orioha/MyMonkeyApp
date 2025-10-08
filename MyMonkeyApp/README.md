# MyMonkeyApp

A small .NET console app that demonstrates fetching and displaying monkey data.

This repository contains the application and build artifacts for `MyMonkeyApp`.

## Project overview

The app retrieves a list of monkey data (name, location, description, image) and prints or uses that data within the application. It is a simple demonstration project intended to show basic HTTP data access and display within a .NET app.

## Requirements

- .NET SDK 9.0 (or compatible) installed. Verify with `dotnet --version`.
- Git (optional, for cloning and pushing changes).

## Build and run

From the repository root (where `MyMonkeyApp.csproj` lives) run:

```powershell
cd c:\Users\ohayon\Code\monkeyApp\MyMonkeyApp\MyMonkeyApp
dotnet build
dotnet run --project MyMonkeyApp.csproj
```

If you just want to run the compiled executable (after a build), run:

```powershell
dotnet bin\Debug\net9.0\MyMonkeyApp.dll
```

## Data

The monkey sample data can be fetched from the project's local data source or a sample remote service. Example dataset used elsewhere:

https://raw.githubusercontent.com/jamesmontemagno/app-monkeys/master/monkeys.json

## Tests

This project currently has no automated tests. If you add tests, include instructions here for running them (for example `dotnet test`).

## Contributing

Contributions are welcome. Please open issues or pull requests. This README was added to address: https://github.com/orioha/MyMonkeyApp/issues/1

## Contact

If you have questions, open a GitHub issue on the repository.
