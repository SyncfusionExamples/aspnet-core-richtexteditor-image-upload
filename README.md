# ASP.NET CORE RichTextEditor - Image Upload

A sample demonstrating how to integrate Syncfusion EJ2 RichTextEditor with ASP.NET Core for image upload and storage using controller actions.

## Prerequisites

* Visual Studio 2022
* .NET Core 2.1 SDK or higher
* Syncfusion EJ2 AspNet.Core package

## Installation Steps

1. Clone or download this repository
2. Open the solution file in Visual Studio 2022
3. Rebuild the solution to restore NuGet packages
4. The wwwroot/Uploads directory is created at runtime

## How to Run the Project

1. Press F5 or click Run in Visual Studio 2022
2. The application opens in your default web browser
3. The RichTextEditor interface loads on the home page
4. Use the image insert feature to upload images to wwwroot/Uploads
5. Uploaded images persist and can be reused in the editor

## Project Details

This project demonstrates:
- **RichTextEditor Integration**: Syncfusion EJ2 RichTextEditor control for content editing
- **Image Upload Handler**: POST action in HomeController to process and save images
- **File System Management**: Creates upload directories and manages file storage
- **ASP.NET Core MVC**: Built on ASP.NET Core 2.1 framework with modern patterns
- **Server-Side Processing**: Handles file validation and secure image storage

The SaveImage action accepts uploaded files, extracts filenames, creates directories, and persists images with error handling.

