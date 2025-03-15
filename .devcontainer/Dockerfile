FROM node:23-bookworm-slim

# Add basic development tools
RUN apt-get update && apt-get install -y git

# Set working directory
WORKDIR /workspace

# Use non-root user for better security
USER node
