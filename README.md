# CI/CD Pipeline with Jenkins and Docker

This project demonstrates how to set up a CI/CD pipeline using Jenkins and Docker for a simple application. The pipeline includes automated testing and deployment in Docker containers.

## Technologies Used
- Jenkins
- Docker
- Git
- Node.js

## Objective
Configure and manage a CI/CD pipeline covering the following stages:
1. Application build
2. Automated testing
3. Docker image creation
4. Application deployment in a Docker container

## Project Structure
ci-cd-jenkins-docker
├── app
│ ├── Dockerfile
│ ├── app.js
│ ├── package.json
│ └── test
│ └── app.test.js
└── Jenkinsfile


## Setup and Execution

### Prerequisites
- Jenkins installed and configured
- Docker installed
- Git installed and a Git repository configured

### 1. Clone the repository
Clone this repository to your local machine:
```bash
git clone https://github.com/your-username/ci-cd-jenkins-docker.git
cd ci-cd-jenkins-docker
