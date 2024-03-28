FROM mcr.microsoft.com/devcontainers/base:bullseye

RUN apt-get update && \
    apt-get install -y \
        curl \
        unzip \
        wget \
        lsb-release \
        gnupg \
        python3 \
        python3-pip \
        libpq-dev \
        postgresql-client \
        && apt-get clean
