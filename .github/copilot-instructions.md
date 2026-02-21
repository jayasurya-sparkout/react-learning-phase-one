# Copilot Instructions for React Learning Phase One

Welcome to the React Learning Phase One project! This document provides guidance for AI coding agents to effectively contribute to this codebase. Please follow these instructions to ensure consistency and alignment with the project's structure and goals.

## Project Overview
This project is a React application bootstrapped with [Create React App](https://github.com/facebook/create-react-app). It is designed as a learning platform for React development, focusing on foundational concepts and best practices.

### Key Files and Directories
- **`src/`**: Contains the main source code for the application.
  - **`App.js`**: The root component of the application. This is the starting point for understanding the app's structure.
  - **`index.js`**: The entry point for rendering the React application.
  - **`App.css`** and **`index.css`**: Stylesheets for the application.
  - **`App.test.js`**: Contains test cases for the `App` component.
  - **`reportWebVitals.js`**: Used for measuring app performance.
  - **`setupTests.js`**: Configures the testing environment.
- **`public/`**: Contains static assets such as `index.html`, `manifest.json`, and `robots.txt`.
- **`package.json`**: Defines project dependencies and scripts.

## Developer Workflows

### Running the Application
To start the development server, use the following command:
```bash
npm start
```
This will launch the app in development mode at [http://localhost:3000](http://localhost:3000). The app will automatically reload when you make changes to the source code.

### Running Tests
To run the test suite in watch mode, use:
```bash
npm test
```
This will execute the tests defined in `src/App.test.js` and any additional test files you create.

### Building for Production
To create an optimized production build, run:
```bash
npm run build
```
The build artifacts will be stored in the `build/` directory.

### Ejecting the Configuration
If you need to customize the build configuration, you can eject it using:
```bash
npm run eject
```
**Note**: This is a one-way operation and cannot be undone.

## Project-Specific Conventions
- **Component Structure**: Follow the functional component pattern with hooks for state and lifecycle management.
- **CSS Modules**: Use `App.css` and `index.css` for styling. Keep styles scoped to their respective components.
- **Testing**: Write tests for all components in the `src/` directory. Use Jest and React Testing Library for unit and integration tests.

## External Dependencies
- The project relies on the default dependencies provided by Create React App, including React, React DOM, and Web Vitals.
- Additional dependencies can be added via `npm install` and should be documented in `package.json`.

## Integration Points
- The app is designed to be extended with additional components and features. New components should be added to the `src/` directory and imported into `App.js` or other relevant components.
- Ensure that any new features are accompanied by appropriate tests and documentation.

## Notes for AI Agents
- Focus on maintaining the simplicity and readability of the code.
- Avoid introducing unnecessary complexity or external dependencies unless absolutely required.
- Follow the existing patterns and conventions in the codebase.
- When in doubt, refer to the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started) for guidance.

Thank you for contributing to the React Learning Phase One project! If you have any questions or need further clarification, please reach out to the project maintainers.