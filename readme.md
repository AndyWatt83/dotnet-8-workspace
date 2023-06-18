#.NET 8 workspace / playground

This repo sets up a ddevcontainer with .NET 8preview 5 installed, allowing access to the new features in this version without having to make changes toan existing development environment.

## How to use
This requires
- Visual Studio Code with the Remote Containers extension installed.
- Docker Desktop

To run:

1. Open this folder in Visual Studio Code
2. Hit F1, and select `rebuild and reopen in conteiner`
3. That's it! Start building in.NET 8!

To get started, use the terminal to issue: `dotnet new console -n dotnet-8-console-app`.

## Changing .NET versions.
If you want to use .NET 7 for comparison, you can set the version in global.json to `7.0.202`

## Useful commands

`dotnet --list-sdks`