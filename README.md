# Import text file into Blazor Rich Text Editor

Import the text file into the Rich Text Editor content using file uploader component, and get the text file content from uploader success event. Then, you can able to import the text file values to the editor.

## Project Overview

This sample shows how to use a file uploader to select a text file, handle the uploader success event to read the file contents, and import the resulting text into the Rich Text Editor for editing or display.

## Key Points

- Uses the file uploader to pick and upload a text file
- Handles uploader success event to retrieve file contents
- Imports text into the Rich Text Editor

## Prerequisites

- .NET 8.0 SDK
- Visual Studio 2022+ or VS Code
- Syncfusion license (if required by project packages)

## Setup & Running Steps

Installation

```bash
git clone https://github.com/SyncfusionExamples/import-text-file-to-blazor-rich-text-editor.git
cd import-text-file-to-blazor-rich-text-editor
```

Restore NuGet packages

```bash
dotnet restore
```

Run the application

```bash
dotnet run
```

## Usage

Start the app, open the importer page, use the file uploader to select a `.txt` file, and on upload success the sample reads the file content and inserts it into the editor.

## Troubleshooting

- Ensure NuGet packages are restored and the project builds before running.
- If content does not import correctly, verify the uploader success handler and any text parsing logic.

## See also

- [Online examples](https://blazor.syncfusion.com/demos/rich-text-editor/overview?theme=fluent)
- [Documentation](https://blazor.syncfusion.com/documentation/rich-text-editor/getting-started)

