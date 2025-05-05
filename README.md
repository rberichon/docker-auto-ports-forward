# Docker Port Forwarder

🌀 A dynamic tool to auto-forward ports from a running Docker container to your host using `socat`, just like VSCode DevContainers — but without VSCode!

## Features

- 🔄 Automatically detects new listening ports in the container
- 🧼 Closes host ports when no longer needed
- 🔁 Handles localhost-only ports via `socat` reverse proxy inside container
- 🌈 Color-coded output for clarity

## Requirements

- Docker
- socat

## Installation

```bash
chmod +x docker-port-forwarder
./docker-port-forwarder
```
