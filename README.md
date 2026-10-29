# Filtering Options in Syncfusion Blazor TreeGrid

## Overview

This sample demonstrates how to work with filtering options in the Syncfusion [Blazor TreeGrid](https://www.syncfusion.com/blazor-components/blazor-tree-grid). The implementation focuses on hierarchical and tabular data filtering scenarios using Excel-like filtering, parent-child filter hierarchy modes, and column-level configurations. These features help users efficiently search, isolate, and analyze structured parent-child records in data-intensive applications.

## Key Features

- Demonstrates Excel-like filter dialogs (`FilterType.Excel`) for intuitive checkbox and search-based filtering across hierarchical data.
- Shows filter hierarchy modes (`FilterHierarchyMode.Parent`) to retain and visualize parent context when child records match filter criteria.
- Illustrates column-level filtering setup across different data types including text, numeric, date, and boolean fields.
- Uses Blazor WebAssembly (.NET 10) architecture with client-side interactive rendering for responsive grid filtering.
- Provides practical examples of organizing and navigating multi-level task data using Syncfusion Blazor TreeGrid.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0)

## Project Structure

```
├── App.razor
├── _Imports.razor
├── Program.cs
├── TreeGridFilteringOptions.csproj
├── Layout/               # MainLayout
├── Pages/                # Home (TreeGrid filtering sample), NotFound
├── Properties/           # launchSettings.json
└── wwwroot/              # index.html, CSS styles, Bootstrap
```

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the project file:

   `TreeGridFilteringOptions.csproj`

3. Restore all NuGet packages.
4. Build the project.
5. Run the application using **Ctrl+F5**.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the repository root.

```bash
cd filtering-options-in-blazor-treegrid
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation for this feature: https://help.syncfusion.com/grid-sdk/blazor/tree-grid/filtering
- Online demos: https://blazor.syncfusion.com/demos/tree-grid/default-filtering

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
