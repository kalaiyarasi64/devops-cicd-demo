# DevOps CI/CD Demo

A simple web application demonstrating Docker containerization and CI/CD automation using GitHub Actions.

## Technologies Used

- HTML
- Docker
- Docker Compose
- Git
- GitHub
- GitHub Actions
- Nginx

## Project Workflow

Developer pushes code to GitHub.

GitHub Actions automatically:

1. Checks out the source code
2. Builds the Docker image
3. Runs the application container
4. Tests the application
5. Stops the test container

## Run Locally

Clone the repository:

    git clone https://github.com/kalaiyarasi64/devops-cicd-demo.git

Go to the project directory:

    cd devops-cicd-demo

Start the application:

    docker compose up -d

Open in browser:

    http://localhost:8080

Stop the application:

    docker compose down

## CI/CD Pipeline

    Code Push
        ↓
    GitHub
        ↓
    GitHub Actions
        ↓
    Docker Build
        ↓
    Container Run
        ↓
    Application Test
        ↓
    Pipeline Success