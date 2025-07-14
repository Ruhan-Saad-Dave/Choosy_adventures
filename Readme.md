# Choice Adventures

Welcome to Choice Adventures, an interactive story generator where you can create and play unique adventure stories! This project consists of a backend API (built with FastAPI) that generates the stories using AI, and a frontend web application (built with React) where you can experience these adventures.

## Features

-   **Generate Stories**: Simply provide a theme, and our AI will craft a brand new interactive story for you.
-   **Play Interactive Adventures**: Make choices throughout the story, and see how your decisions shape the narrative.
-   **Restart and Replay**: Enjoy your favorite stories multiple times, exploring different paths and endings.

## Getting Started

To get started with Choice Adventures, you'll need to run both the backend and frontend services. Follow the steps below:

### Prerequisites

Before you begin, ensure you have the following installed on your system:

-   **Python 3.9+**: For the backend.
-   **Node.js (LTS version)**: For the frontend.
-   **npm** (Node Package Manager) or **yarn**: Comes with Node.js.
-   **uv**: A fast Python package installer and resolver. You can install it using pip: `pip install uv`

### 1. Backend Setup and Run

Navigate to the `backend` directory and follow its instructions:

```bash
cd backend
uv pip install -r requirements.txt
uvicorn main:app --reload
```

The backend API will be running at `http://localhost:8000`. You can access the API documentation at `http://localhost:8000/docs`.

### 2. Frontend Setup and Run

Open a new terminal, navigate to the `frontend` directory, and follow its instructions:

```bash
cd frontend
npm install
npm run dev
```

The frontend application will typically be available at `http://localhost:5173` (or another port if 5173 is in use). Your browser should automatically open to this address.

### 3. Enjoy Your Adventure!

Once both the backend and frontend are running, open your web browser and go to the frontend URL (e.g., `http://localhost:5173`). You can then start generating and playing your own choice adventures!

## Project Structure

-   `backend/`: Contains the FastAPI backend application.
-   `frontend/`: Contains the React frontend application.
-   `README.md`: This file, providing an overview of the entire project.

## Contributing

We welcome contributions! If you'd like to contribute, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.