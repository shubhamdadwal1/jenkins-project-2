# 🚀 Jenkins Project 2 – CI/CD with Docker and Kubernetes

![Jenkins](https://img.shields.io/badge/Jenkins-CI%2FCD-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containerization-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-Web%20Application-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Version%20Control-181717?style=for-the-badge&logo=github&logoColor=white)

## 📌 Project Overview

This project demonstrates the deployment of a containerized web application using Docker and Kubernetes.

The project contains an HTML web page, a Dockerfile for building the application image, Kubernetes Deployment and Service manifests, and a shell script for testing.

It provides hands-on practice with containerization, application deployment, Kubernetes resource management, and the fundamentals of CI/CD workflows.

## 🎯 Project Objectives

- Build a container image using Docker.
- Package a web application for deployment.
- Deploy the application using Kubernetes.
- Manage application replicas using a Kubernetes Deployment.
- Expose the application using a Kubernetes Service.
- Test application functionality using a shell script.
- Maintain application and infrastructure configuration in GitHub.
- Understand how Jenkins can automate build, test, and deployment steps.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Jenkins | Continuous integration and continuous delivery automation |
| Docker | Building and running container images |
| Kubernetes | Deploying and managing application containers |
| HTML | Creating the web application interface |
| YAML | Defining Kubernetes resources |
| Shell Scripting | Automating testing and command-line tasks |
| Git | Version control |
| GitHub | Source code hosting and collaboration |

## 🏗️ Project Architecture

The project follows this general workflow:

1. Source code is maintained in GitHub.
2. Jenkins can retrieve the source code and execute build steps.
3. Docker builds a container image using the Dockerfile.
4. The image is made available to the Kubernetes cluster.
5. Kubernetes creates and manages application Pods.
6. A Kubernetes Service provides network access to the application.
7. The shell script can be used to perform configured checks.

### Architecture Diagram

```text
                 Developer
                     |
                     v
               GitHub Repository
                     |
                     v
                  Jenkins
                     |
              Build and Test
                     |
                     v
               Docker Image
                     |
              Image Registry
                     |
                     v
             Kubernetes Cluster
                     |
              Kubernetes Pod
                     |
                     v
                Web Application
                     |
                     v
             Kubernetes Service
                     |
                     v
                   Browser
