# HiveBox

An end-to-end DevOps hands-on project that builds a scalable RESTful API 
around openSenseMap to help beekeepers track environmental sensor data.

Built with **.NET 8**.

## Current Status

🚧 Phase 2 — basic app that prints its version.

## Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download) (if running locally without Docker)
- [Docker](https://www.docker.com/get-started)

## Build & Run

### Using Docker (recommended)

Build the image:
\`\`\`bash
docker build -t hivebox:0.0.1 .
\`\`\`

Run the container:
\`\`\`bash
docker run hivebox:0.0.1
\`\`\`

Expected output:
\`\`\`
HiveBox version: 0.0.1
\`\`\`

### Running locally (without Docker)

\`\`\`bash
dotnet run
\`\`\`

## Testing

To verify the app works correctly, run it (via Docker or `dotnet run`) 
and confirm it prints the current version number (`0.0.1`) and exits 
with no errors.

## Roadmap

This project follows the [Dynamic DevOps Roadmap](https://devopsroadmap.io/projects/hivebox/) 
by DevOps Hive.