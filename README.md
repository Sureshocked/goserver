# Go Web Server Docker Example

A simple web server written in Go and containerized with Docker, previously used in a load-balanced environment.

## Project Overview
This project demonstrates:
- Basic Go HTTP server implementation
- Docker containerization of a Go application
- Port mapping and container management
- Integration with Caddy load balancer setup

## Structure
- `main.go` - Simple web server serving HTML content
- `Dockerfile` - Container configuration using debian:stable-slim
- `goserver` - Compiled Go binary (not tracked in git)

## Running Locally
```bash
# Build the Go binary
go build

# Run locally
./goserver
