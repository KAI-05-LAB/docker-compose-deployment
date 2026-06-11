# Automating Application Deployment with Docker Compose

## Objective

This project demonstrates how Docker Compose can be used to manage and deploy multiple containers as a single application.

## What is Docker Compose?

Docker Compose is a tool that allows users to define and run multi-container Docker applications using a YAML configuration file.

## Project Components

### Web Service

* Uses Nginx web server
* Exposes port 8080

### Database Service

* Uses MySQL 8.0
* Creates a sample database

## Docker Compose File

The docker-compose.yml file defines both services and their configurations.

## Commands Used

### Start Services

```bash
docker-compose up -d
```

### View Running Containers

```bash
docker ps
```

### Stop Services

```bash
docker-compose down
```

## Benefits of Docker Compose

* Simplifies multi-container deployment
* Easy service management
* Reproducible environments
* Better application organization

## What I Learned

* Docker Compose fundamentals
* Multi-container application architecture
* Service orchestration concepts
* Container networking basics

## Challenges Faced

Understanding how multiple containers communicate and are managed together was initially challenging. Through studying Docker Compose files and service definitions, I gained a better understanding of container orchestration.
