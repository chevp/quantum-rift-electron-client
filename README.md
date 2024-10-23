# Quantum Rift Electron Client

This project is the **Electron** client application for **Quantum Rift**, built using **TypeScript**. The application provides a desktop client for interacting with the Quantum Rift system, offering a sleek user interface and seamless integration with the backend.

## Features

- **Cross-platform**: Runs on Windows, macOS, and Linux.
- **TypeScript Integration**: Strongly-typed client-side code for improved maintainability.
- **Electron Framework**: Combines the power of web technologies (HTML, CSS, JavaScript) with native desktop capabilities.
- **Real-time Communication**: Interacts with Quantum Rift backend services to provide up-to-date data.
- **Customizable UI**: Modify and extend UI components with ease.
  
## Requirements

- **Node.js** (>=14.x)
- **npm** (>=6.x)
- **Electron** (>=15.x)

## Setup

### 1. Clone the repository:

```bash
git clone https://github.com/chevp/quantum-rift-electron-client.git
cd quantum-rift-electron-client
```

### 2. Install dependencies:

```bash
npm install
```

### 3. Start the Electron app:

```bash
npm start
```

The app will start in a new Electron window. You can also build it for different platforms using Electron Packager.

## Building for Production

To package the app for distribution:

```bash
npm run build
```

### Packaging for Specific Platforms:

To package for **Windows**, **macOS**, or **Linux**, you can run:

```bash
npm run package:win   # for Windows
npm run package:mac   # for macOS
npm run package:linux # for Linux
```

## Folder Structure

```
├── src/                     # Source code
│   ├── main/                # Main Electron process
│   ├── renderer/            # Renderer (UI) process
├── dist/                    # Compiled output for production
├── package.json             # npm scripts and dependencies
├── tsconfig.json            # TypeScript configuration
├── webpack.config.js        # Webpack configuration for bundling
└── README.md                # This README file
```

## Development

To enable hot reloading and faster development, you can run:

```bash
npm run dev
```

This command will start the app in development mode with live-reloading enabled, so you can test changes without restarting the app.

## License

This project is licensed under the MIT License.
