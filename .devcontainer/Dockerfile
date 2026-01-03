FROM mcr.microsoft.com/devcontainers/javascript-node:22

# Install dependencies for building native modules
RUN apt-get update && apt-get install -y \
    build-essential \
    && rm -rf /var/lib/apt/lists/*

# Set working directory
WORKDIR /workspaces
