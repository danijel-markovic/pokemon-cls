# Use the official Python 3.10 image as the base image
FROM python:3.10

RUN apt-get update
# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install the dependencies from the requirements.txt file
RUN pip install --no-cache-dir -r requirements.txt


