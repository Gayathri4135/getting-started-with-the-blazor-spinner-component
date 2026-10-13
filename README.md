# Getting Started with the Blazor Spinner Component

## Overview

This sample demonstrates how to use the Syncfusion [Blazor Spinner](https://www.syncfusion.com/forums) component in a hosted Blazor WebAssembly application. The implementation showcases displaying loading indicators for long-running operations, customizing spinner appearance, and controlling visibility during user interactions.

The sample integrates the Spinner component with the Syncfusion Tab component to provide visual feedback while tab content is being loaded. It also demonstrates custom styling, descriptive labels, and visibility management using two-way binding and asynchronous event handling.

## Key Features

- Demonstrates the Syncfusion Blazor Spinner component.
- Shows and hides spinners using the `Visible` property.
- Supports `Bootstrap5` and `Bootstrap` spinner types.
- Displays custom loading labels using the `Label` property.
- Applies custom styling through `CssClass` and CSS customization.
- Uses `@bind-Visible` for two-way visibility binding.
- Integrates Spinner with the Syncfusion Tab component.
- Uses `Selecting` and `Selected` tab events to manage loading states.
- Demonstrates asynchronous spinner visibility control.
- Includes sample usage of `ShowAsync()` and `HideAsync()` methods.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `GettingStarted.sln` solution file.
3. Restore NuGet packages.
4. Build the solution.
5. Run the application using **Ctrl+F5**.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the startup project directory for the hosted application.

```bash
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `GettingStarted.sln` — Visual Studio solution file containing the sample projects.

`Client/Pages/Index.razor` — Main sample page demonstrating Spinner customization, labels, visibility control, and Tab integration.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://blazor.syncfusion.com/documentation/progress-bar/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.