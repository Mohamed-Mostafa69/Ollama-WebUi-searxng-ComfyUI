# Ollama-WebUi-searxng-ComfyUI


## Overview

This project sets up a private AI environment with advanced capabilities including image generation, web search integration, voice transcription, and text-to-speech. The setup is built using Docker and Docker Compose for streamlined deployment and management.

## Tools Used

- **Docker & Docker Compose**: For containerizing and managing the various components.
- **Ollama**: Powers and serves the AI model.
- **OpenWebUI**: Provides a user-friendly interface and allows for easy integration with other tools.
- **SearxNG**: Handles web search functionalities.
- **ComfyUI**: Manages image generation tasks.
- **FOR Ollama and ComfyUI you have to download A Model

## Getting Started

### Prerequisites

- Docker
- Docker Compose
- install an Ollama Model
- install ComfyUI Model make sure its an checkpoint and store it in ComfyUI/model/checkpointi
- run ComfyUI native

### Installation

1. Clone the repository:
   ```bash
   git clone
   cd Ollama-WebUi-searxng-ComfyUI

2. Configure your environment:

- **Update the environment variables in the docker-compose.yml file to match your setup.
- **Modify the settings in OpenWebUI to align with your web search and image generation requirements.

3. Start the services:

   docker-compose up -d

## Resources

- **Ollama: https://ollama.com/library/llama3.1
- **Open-WebUI: https://github.com/open-webui/open-webui
- **SearxNG: https://github.com/searxng/searxng
- **ComfyUI: https://github.com/comfyanonymous/ComfyUI
- **Downloading image model: https://civitai.com/



## Running ComfyUI

ComfyUI runs natively outside of Docker. Ensure it is set up and configured separately.

Additional Steps
For enhanced performance and flexibility:

GPU Acceleration: Run Docker containers with GPU support to boost AI performance.
ComfyUI in Docker: Create a GPU-accelerated Docker container for ComfyUI and add it to your Docker Compose setup for easier management.

