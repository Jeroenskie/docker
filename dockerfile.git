# Trek laatste ubuntu van server
FROM ubuntu:latest

# Set one or more individual labels
LABEL com.example.version="0.0.1-beta"
LABEL vendor="Jeroenskie"
LABEL com.example.release-date="23-11-2016"
LABEL com.example.version.is-production="euhh"

# Install de volgende utilities
RUN apt-get update && apt-get install -y \
  apt-utils \
  git \
  vim
