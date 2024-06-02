# Simple Electron App

This is a simple Electron application that demonstrates a basic setup of an Electron project. The application opens a window that displays the versions of Node.js, Chromium, and Electron being used.

## Features

- **Electron**: Uses Electron to create a desktop application.
- **Preload Script**: Displays the versions of Node.js, Chromium, and Electron.
- **Basic HTML Interface**: Shows version information in the application window.

## Getting Started

To get started with this Electron app, follow these steps:

### Prerequisites

- [Node.js](https://nodejs.org/) (v14.x or later)
- [Yarn](https://yarnpkg.com/) (optional, you can use npm if you prefer)

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/Saadaan-Hassan/First-Electron-App.git
   cd First-Electron-App
   ```

2. **Install dependencies:**

   Using Yarn:

   ```sh
   yarn install
   ```

   Or using npm:

   ```sh
   npm install
   ```

### Running the Application

To start the application, run:

Using Yarn:

```sh
yarn start
```

Or using npm:

```sh
npm start
```

This will open the Electron application window displaying the versions of Node.js, Chromium, and Electron.

## Building the Application

To build the application for distribution, run:

Using Yarn:

```sh
yarn make
```

Or using npm:

```sh
npm run make
```

The built distributables will be located in the out directory.

## Publishing the Application

To publish the application, ensure you have set up a `GITHUB_TOKEN` environment variable with the necessary permissions. Then, run:

Using Yarn:

```sh
yarn publish
```

Or using npm:

```sh
npm run publish
```

This will publish your application to the specified GitHub repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgements

- [Electron](https://www.electronjs.org/) - Build cross-platform desktop apps with JavaScript, HTML, and CSS.
- [Node.js](https://nodejs.org/) - JavaScript runtime built on Chrome's V8 JavaScript engine.
- [Chromium](https://www.chromium.org/) - Fast, reliable, and secure dependency management.
