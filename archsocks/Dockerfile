# Use an official Python runtime as a parent image
FROM python:3.4

# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
ADD . /app


# Make port 80 available to the world outside this container
EXPOSE 9501

# Define environment variable
ENV NAME World

# Run app.py when the container launches
CMD ["archsocks"]
