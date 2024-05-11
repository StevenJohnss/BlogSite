# React JS Blog Site

This project is a simple front-end blog site built with React JS. It allows users to log in, create posts, and view them. The application uses Material-UI for styling and React Router for navigation.

## Features

- User authentication
- Create blog posts with title, tags, category, and file attachments
- View and sort blog posts
- Responsive design for various screen sizes

## Installation

To get started with this project, clone the repository and install the dependencies:

```bash
git clone <repository-url>
cd <project-directory>
npm install
```

## Usage

To run the application in development mode:

```bash
npm start
```

This will start the development server and open the application in your default web browser.

## Building for Production

To create a production build:

```bash
npm run build
```

This command builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance.

## Dependencies

- React
- Material-UI
- React Router
- React Toastify for notifications

## Structure

- `src/index.js`: Entry point of the application.
- `src/App.js`: Main component that handles routing.
- `src/login.js`: Handles user authentication.
- `src/Homepage_componants/Home.js`: Main component for the homepage that includes post creation and display.
- `src/Homepage_componants/Displaydata.js`: Component to display posts with sorting and searching functionality.

Live URL: https://dazzling-aryabhata-ea34f7.netlify.app/
