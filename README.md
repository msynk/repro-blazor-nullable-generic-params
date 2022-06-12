# repro-blazor-nullable-generic-params
This repository demonstrates an ASP.NET Core bug. There is an incorrect warning when compiling `src\BlazorApp1\Components\MyComponent.razor` using `dotnet build` with a clean source code (e.g. without the `obj` folder) on dotnet sdk version `6.0.300`
