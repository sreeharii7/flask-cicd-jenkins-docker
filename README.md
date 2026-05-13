# Flask CI/CD Pipeline with Jenkins and Docker

A fully automated CI/CD pipeline that builds, containerises, and deploys 
a Flask web application using Jenkins, Docker, and Docker Compose.

## Architecture
## Tech Stack

| Tool | Purpose |
|------|---------|
| Python / Flask | Web application |
| Docker | Containerisation |
| Docker Compose | Multi-container orchestration |
| Jenkins | CI/CD pipeline automation |
| MySQL | Database tier |
| GitHub | Source control |

## Pipeline Stages

1. **Code Checkout** — Jenkins clones the latest code from GitHub
2. **Docker Build** — Builds the Flask app image from Dockerfile
3. **Deploy** — Docker Compose spins up Flask + MySQL containers

## How to Run Locally

```bash
# Clone the repo
git clone https://github.com/sreeharii7/Dockerfile.git
cd Dockerfile

# Start the application
docker-compose up --build

# Access the app
http://localhost:5000
```

## Project Structure
## What I Learned

- Building and managing Docker images and containers
- Orchestrating multi-tier applications with Docker Compose
- Automating deployments with Jenkins pipeline stages
- Debugging container startup issues using Docker logs
