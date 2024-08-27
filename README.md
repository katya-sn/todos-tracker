# Todos Tracker

[DEMO LINK](https://katya-sn.github.io/todos-tracker/)

This project is a Todo Management application, designed as a single-page app using React and TypeScript. It allows users to manage their todos efficiently, with features like adding, updating, deleting, and filtering tasks. The app is built to be scalable and maintainable, utilizing React's Context API for state management and the Fetch API for data handling.

## Main Technologies Used
1. **React**: The application is developed using React with functional components for managing UI and logic.
2. **TypeScript**: TypeScript is employed to ensure type safety and improve code quality across the project.
3. **Context API**: React's Context API is used for global state management, providing a clean and scalable solution to handle application state.
4. **Fetch API**: The app communicates with a backend service using the Fetch API to manage todos, with requests for getting, adding, updating, and deleting todos.
5. **SCSS**: SCSS is used for styling, offering powerful features like variables, nesting, and mixins for a more maintainable CSS structure.

## Features
1. **Global State Management**: The app uses Context API to manage the state of todos, filter options, and error messages across the application.
2. **Todo Operations**: Users can add new todos, update existing ones, and delete todos they no longer need.
3. **Filtering**: Todos can be filtered based on their status (all, active, or completed) to help users focus on specific tasks.
4. **Persistent Data**: Todos are fetched from and stored on the server, ensuring that user data is persistent across sessions.
Error Handling: The app includes error handling mechanisms to manage failed requests and display appropriate error messages to users.

## How to Run the Page Locally
1. Clone the repository to your local machine using the command **`git clone https://github.com/katya-sn/todos-tracker.git`**.
2. Then, navigate to the project directory using **cd todos-tracker**.
3. Make sure you have Node.js and npm installed, and install the project dependencies by running **`npm install`**.
4. After the dependencies are installed, start the development server with **`npm start`**.
5. Finally, open your browser and go to **http://localhost:3000** to see the Landing running locally.
