# TodoApi 

## Notes

To Scaffold a controller, run the following commands:

dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet tool install -g dotnet-aspnet-codegenerator
dotnet tool update -g dotnet-aspnet-codegenerator
dotnet aspnet-codegenerator controller -name TodoItemsController -async -api -m TodoItem -dc TodoContext -outDir Controllers


Add NuGet packages required for scaffolding.
-- Installs the scaffolding engine (dotnet-aspnet-codegenerator).
Scaffolds the TodoItemsController.

## 
## CSharp SoSharp

The Id property functions as the unique key in a relational database.

Model classes can go anywhere in the project, but the Models folder is used by convention.

## Resources
https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-5.0&tabs=visual-studio-mac

## Questions
