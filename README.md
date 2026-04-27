# Getting Started Todo App

A simple todo application built with Node.js and MySQL.

## Running with Docker

```bash
docker-compose up
```

The app will be available at `http://localhost:3000`

## GitHub Actions CI/CD Pipeline

This repository has a GitHub Actions workflow that:
- Installs dependencies
- Runs tests
- Runs linting
- Builds the application
- Builds Docker images

The workflow runs on every push to `main` and on pull requests.
