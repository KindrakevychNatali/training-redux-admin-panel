
# Redux Admin Panel

This project is a **Redux Admin Panel** built with **React** and pure **Redux**. It features a management interface for handling data, with a focus on leveraging modern React and Redux practices. The project also includes styling via Bootstrap and Sass, and runs a mock backend using JSON Server.

## Features

- **Redux**: Simplified Redux logic with slices, reducers, and async thunks.
- **React-Redux**: Connects React components to the Redux store.
- **JSON Server**: Provides a mock REST API for development.
- **Bootstrap 5**: Responsive, mobile-first UI framework.
- **Sass**: Enables advanced CSS styling with nesting, variables, and more.
- **UUID**: Generates unique IDs for handling data.
- **Concurrently**: Runs multiple npm scripts simultaneously, e.g., React app and JSON server.

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (LTS version recommended)
- [npm](https://www.npmjs.com/) (Comes bundled with Node.js)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/KindrakevychNatali/training-redux-admin-panel.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd training-redux-admin-panel
   ```

3. **Install the dependencies**:

   ```bash
   npm install
   ```

4. **Start the development server**:

   ```bash
   npm start
   ```

   This command starts the React development server and the JSON server on port `3001` concurrently. The React app runs on [http://localhost:3000](http://localhost:3000).

### Project Structure

```plaintext
training-redux-admin-panel/
├── public/              # Static assets
├── src/
│   ├── components/      # Reusable UI components
│   ├── features/        # Redux slices and async actions
│   ├── pages/           # Application page components
│   ├── styles/          # Global styles (Sass)
│   ├── App.js           # Root application component
│   ├── index.js         # React entry point
│   └── ...
├── heroes.json          # Mock data for JSON server
├── .gitignore           # Files and directories to ignore in git
├── package.json         # Project configuration and dependencies
└── README.md            # Project overview and documentation
```

### Available Scripts

- **`npm start`**: Runs the app in development mode. Starts both the React app and JSON server.
- **`npm run build`**: Builds the app for production in the `build` folder.
- **`npm test`**: Launches the test runner in the interactive watch mode.
- **`npm run eject`**: Ejects the project from `create-react-app` to allow custom configurations.

### Dependencies

- **`@reduxjs/toolkit`**: Simplifies Redux logic with powerful abstractions.
- **`react-redux`**: Efficiently binds React components to the Redux store.
- **`redux-thunk`**: Middleware to handle asynchronous logic in Redux.
- **`reselect`**: Library for creating memoized selectors for efficient Redux state computation.
- **`bootstrap`**: CSS framework for responsive and mobile-first web design.
- **`sass`**: CSS preprocessor to enhance styles with variables, nesting, and more.
- **`uuid`**: Utility for generating unique IDs.
- **`classnames`**: Utility to conditionally join class names.
- **`concurrently`**: Utility to run multiple npm commands concurrently (used to start React and JSON server together).

### Development and Contribution

To contribute to this project:

1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

### License

This project is licensed under the ISC License. You are free to use, modify, and distribute it.

---
