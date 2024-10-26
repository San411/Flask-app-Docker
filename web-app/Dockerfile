# Use python:3.9-slim as the base image
FROM python:3.9-slim

# Set a working directory in the container
WORKDIR /app

# Copy the API source code to the working directory
COPY . /app

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Container uses the port 5000
EXPOSE 5000

# Command to run the application
CMD ["python", "app.py"]
