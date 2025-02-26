FROM ubuntu:latest

# Set working directory
WORKDIR /app

# Copy everything into /app directory
COPY . /app

# Install Python and pip
RUN apt-get update && apt-get install -y python3 python3-pip

# Run the app
CMD ["python3", "app.py"]
