# Use the official Ubuntu 20.04 image from Docker Hub
FROM ubuntu:20.04

# Set environment variable to avoid interactive prompts during installation
ENV DEBIAN_FRONTEND=noninteractive

# Update the system and install a few basic programs (this is optional)
RUN apt-get update && apt-get upgrade -y && apt-get install -y \
    build-essential \
    curl \
    wget \
    nano

# Set a working directory inside the container
WORKDIR /workspace

# Start a bash shell when the container starts
CMD [ "bash" ]
