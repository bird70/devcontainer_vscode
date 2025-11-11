# Python 3 DevContainer Dockerfile with uv
FROM mcr.microsoft.com/devcontainers/python:3.11

# Install uv (fast Python package manager)
RUN pip install --upgrade pip && pip install uv

# Set up a default workdir
WORKDIR /workspace

# Optionally, install other system dependencies here
# RUN apt-get update && apt-get install -y <package>

# Default command
CMD ["/bin/bash"]
