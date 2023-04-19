# Minecraft Server (Bedrock Edition) using Docker Compose

## Overview 🔎

- An easy to setup Minecraft Bedrock Edition Server that runs on Windows, Mac and Linux

## Requirements 📝

- Docker Desktop [(download here)](https://www.docker.com/products/docker-desktop/)

## Instructions 🛠️

1. Using Command Prompt on Windows, or Terminal on Mac and Linux, navigate to this project's directory.
2. Create a file named `.env` and open it with any text editor. Copy and paste everything from `.env.sample` into it.
3. Modify the values according to your needs
4. Run the following commands

```console
docker compose pull
docker compose up
```

## Cleanup 🗑️

Simply run `docker compose down` and delete everything inside the data folder.
