FROM pytorch/pytorch:2.2.1-cuda12.1-cudnn8-devel
# Install system dependencies
RUN apt-get update && apt-get install -y \
    libjpeg-dev \
    zlib1g-dev \
    git && \
    rm -rf /var/lib/apt/lists/*


# Use bash as the default shell
SHELL ["/bin/bash", "-c"]