
# DevOps AWS Docker CI/CD Project

## Project Overview

This project demonstrates a real-world DevOps workflow
for building, testing, containerizing, and deploying a
Python web application to AWS EC2 using GitHub Actions.

## Project Goals

- Develop a Python web application
- Manage source code using Git and GitHub
- Containerize the application using Docker
- Deploy the application to AWS EC2
- Build a CI/CD pipeline using GitHub Actions
- Apply cloud security best practices
- Monitor and troubleshoot the application

## Technology Stack

- Ubuntu 24.04 (WSL2)
- Git and GitHub
- Python
- Docker
- GitHub Actions
- AWS EC2
- Linux

## Architecture

Planned deployment workflow:

Developer
    |
    v
GitHub Repository
    |
    v
GitHub Actions (CI/CD)
    |
    v
Container Registry
    |
    v
AWS EC2
    |
    v
Docker Container
    |
    v
Python Web Application

## Project Status

In progress - Phase 3: Git Repository Setup

## Security

- Never commit AWS credentials or private keys.
- Use least-privilege IAM permissions.
- Use SSH keys for GitHub authentication.
- Configure network access using security groups.
- Monitor AWS costs and resource usage.

## Documentation

Detailed implementation, architecture, troubleshooting,
and cleanup instructions will be added as the project
progresses.
