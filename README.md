# Dockerized Node.js App with CI/CD Pipeline

This is a demo replication of a client project showcasing a Dockerized Node.js application integrated with a CI/CD pipeline using GitHub Actions.

## Stack
- Node.js
- Express
- Docker
- GitHub Actions (CI/CD)
- Docker Compose (for local development)

## What This Project Does
- Automatically builds and tests on every push to `main`
- Uses GitHub Actions to simulate production-ready CI/CD
- Local development with Docker Compose

## Run Locally

```bash
docker-compose up --build

```
- App will be available at: http://localhost:3000

## CI/CD Pipeline
- Trigger: Push to main
- Steps: Install → Lint → Test → Docker Build

## Folder Structure
- app/ – Contains the Node.js express app
- .github/workflows/ – CI/CD pipeline YAML

## GitHub Actions Pipeline
- Push to main branch triggers:

- Lint & test the app
- Build Docker image
- Push image (stubbed – simulated)
- Deploy (stubbed)

- Note: Secrets, production scripts, and credentials are removed or stubbed.

Author
👤 Sameer Anwaar Hussain – Freelance DevOps Engineer
📬 Open to work | Available for part-time/full-time freelance
