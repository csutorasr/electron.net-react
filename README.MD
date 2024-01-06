# Electron DotNet React Example

This is a simple example of how to use Electron with React and DotNet Core.

## Getting Started

You'll need [Node.js (v.12.x)](https://nodejs.org) and [.NET Core SDK](https://www.microsoft.com/net/download/core) installed on your computer in order to start or build this app.

```bash
dotnet tool install --global ElectronNET.CLI
electronize start
```  

## How this repository is created

```bash
dotnet new react
dotnet add package ElectronNET.API
electronize init
cd ClientApp
npm install electron -S
npm install vite @vitejs/plugin-react vite-tsconfig-paths -D
# Add vite.config.ts
# move public/index.html to index.html
# rename files from js to jsx
```

Add InfoDialogListener.cs and the emitter to the Counter.js.

