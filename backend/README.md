# Backend

This directory contains the backend of the Choice Adventures application, which is a FastAPI-powered API responsible for generating and managing the interactive stories.

## Features

-   **Story Generation**: Leverages the `langchain-google-genai` library to dynamically create branching narratives based on a given theme.
-   **API**: Provides endpoints for creating stories, checking the status of story generation jobs, and retrieving story data.
-   **Database**: Uses SQLAlchemy to interact with a database for storing stories and their nodes.

## Getting Started

To run the backend server, you will need to have Python and `uv` installed.

1.  **Install Dependencies**:
    ```bash
    uv sync
    ```
2.  **Run the Server**:
    ```bash
    uvicorn main:app --reload
    ```

The API documentation will be available at `http://localhost:8000/docs`.

## Project Structure

-   `main.py`: The main entry point for the FastAPI application.
-   `core/`: Contains the core logic of the application, including the story generation and configuration.
-   `db/`: Manages the database connection and tables.
-   `models/`: Defines the SQLAlchemy models for the database.
-   `routers/`: Contains the API endpoints for different resources.
-   `schemas/`: Defines the Pydantic schemas for data validation.