# 🚢 Containers Demos

Welcome to the **Containers Demos** repository! This project showcases various containerization techniques and examples using Docker and Kubernetes. Whether you're a beginner or an experienced developer, you'll find useful demos that illustrate how to effectively use containers in your projects.

[![Download Releases](https://img.shields.io/badge/Download%20Releases-Click%20Here-brightgreen)](https://github.com/GilHaxz/containers-demos/releases)

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Demos](#demos)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Containers are a powerful tool for developers. They allow you to package applications with all their dependencies into a single unit. This makes it easy to deploy and run applications consistently across different environments. In this repository, you'll find demos that illustrate various aspects of containerization.

## Getting Started

To get started with the demos in this repository, you can download the latest release from our [Releases section](https://github.com/GilHaxz/containers-demos/releases). After downloading, follow the instructions provided in each demo to execute the examples.

### Prerequisites

Before you begin, ensure you have the following installed:

- **Docker**: This is the core technology we will use for containerization. You can download it from [Docker's official website](https://www.docker.com/get-started).
- **Kubernetes**: For orchestration, you'll need Kubernetes. You can set it up using Minikube or any cloud provider.
- **Git**: To clone the repository, make sure you have Git installed.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/GilHaxz/containers-demos.git
   ```
2. Navigate to the directory:
   ```bash
   cd containers-demos
   ```

3. Download the latest release from our [Releases section](https://github.com/GilHaxz/containers-demos/releases). Make sure to execute the downloaded files as per the instructions.

## Demos

In this section, we outline the various demos available in the repository. Each demo has its own directory and contains a README file with detailed instructions.

### 1. Basic Docker Demo

This demo shows how to create a simple Docker container that runs a web server. 

- **Directory**: `basic-docker-demo`
- **Instructions**: 
  1. Navigate to the demo directory.
  2. Build the Docker image:
     ```bash
     docker build -t my-web-server .
     ```
  3. Run the container:
     ```bash
     docker run -p 80:80 my-web-server
     ```

### 2. Docker Compose Demo

Learn how to use Docker Compose to manage multi-container applications.

- **Directory**: `docker-compose-demo`
- **Instructions**:
  1. Navigate to the demo directory.
  2. Start the application:
     ```bash
     docker-compose up
     ```

### 3. Kubernetes Deployment Demo

This demo illustrates how to deploy a simple application on Kubernetes.

- **Directory**: `kubernetes-deployment-demo`
- **Instructions**:
  1. Ensure your Kubernetes cluster is running.
  2. Apply the deployment configuration:
     ```bash
     kubectl apply -f deployment.yaml
     ```

### 4. CI/CD with Containers

Explore how to set up a CI/CD pipeline using containers.

- **Directory**: `cicd-demo`
- **Instructions**:
  1. Follow the README to set up the pipeline with GitHub Actions or Jenkins.

## Usage

Once you have the demos running, you can explore various functionalities. Each demo has its own set of features and configurations. Feel free to modify the code to suit your needs.

### Common Commands

Here are some common Docker commands you might find useful:

- **List Running Containers**:
  ```bash
  docker ps
  ```

- **Stop a Container**:
  ```bash
  docker stop <container_id>
  ```

- **Remove a Container**:
  ```bash
  docker rm <container_id>
  ```

For Kubernetes, some useful commands include:

- **Get Pods**:
  ```bash
  kubectl get pods
  ```

- **Delete a Pod**:
  ```bash
  kubectl delete pod <pod_name>
  ```

## Contributing

We welcome contributions to this repository. If you have ideas for new demos or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/my-feature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add new demo"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/my-feature
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or suggestions, feel free to reach out:

- **Email**: your-email@example.com
- **GitHub**: [GilHaxz](https://github.com/GilHaxz)

Thank you for visiting the **Containers Demos** repository! We hope you find these demos helpful in your containerization journey. Don't forget to check the [Releases section](https://github.com/GilHaxz/containers-demos/releases) for the latest updates and downloads.