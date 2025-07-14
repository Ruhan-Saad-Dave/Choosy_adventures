# Use an official Python runtime as a parent image
FROM python:3.11-slim

# Set the working directory in the container
WORKDIR /app

# Install uv
RUN pip install uv

# Copy the requirements file into the container at /app
COPY ./requirements.txt /app/requirements.txt

# Install any needed packages specified in requirements.txt using uv
RUN uv pip install --no-cache -r requirements.txt

# Copy the rest of the application's code into the container
COPY . /app

# Command to run the application
CMD ["uv", "run", "main.py"]
