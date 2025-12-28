# Harsh Gupta Resume Site (ASP.NET Core)

A minimal ASP.NET Core web app that serves your provided static HTML from `wwwroot/index.html`.

## Prerequisites
- .NET SDK (as installed; templates suggest SDK supports `net10.0`).
- Windows PowerShell.

## Run (Development)
```powershell
Push-Location "d:\Website\Resume.net\resume"
dotnet run --urls http://localhost:5000
```
Browse: http://localhost:5000

## Project Layout
- Program: [Program.cs](Program.cs)
- Static root: [wwwroot](wwwroot)
  - Entry page: [wwwroot/index.html](wwwroot/index.html)

## Publish (Self-contained folder)
```powershell
Push-Location "d:\Website\Resume.net\resume"
dotnet publish -c Release -o .\publish
```
Output will be in `publish/`.
