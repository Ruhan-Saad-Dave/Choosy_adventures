# Frontend

This directory contains the frontend of the Choice Adventures application, which is a React-based web application that allows users to generate and play interactive stories.

## Features

-   **Story Generation Interface**: Provides a user-friendly interface to input themes for story generation.
-   **Interactive Story Playback**: Displays generated stories and allows users to make choices that influence the narrative flow.
-   **Loading Status**: Shows the status of story generation jobs.

## Getting Started

To run the frontend application, you will need to have Node.js and npm (or yarn) installed.

1.  **Install Dependencies**:
    ```bash
    npm install
    ```
2.  **Run the Development Server**:
    ```bash
    npm run dev
    ```

The application will be accessible at `http://localhost:5173` (or another port if 5173 is in use).

## Project Structure

-   `src/App.jsx`: The main React component that sets up routing.
-   `src/main.jsx`: The entry point for the React application.
-   `src/components/`: Contains various React components used to build the UI, such as `StoryGenerator.jsx` and `StoryGame.jsx`.
-   `src/utils.js`: Contains utility functions, including API base URL and session management.
-   `public/`: Contains static assets.
-   `index.html`: The main HTML file.