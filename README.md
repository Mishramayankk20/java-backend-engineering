# Java Backend Engineering

A collection of production-oriented backend projects built with Java and Spring Boot, alongside full-stack and container orchestration projects.

The repository focuses on:

- REST API design
- Microservices architecture
- Service discovery
- Inter-service communication
- Fault tolerance
- Rate limiting
- Database design
- Containerization and orchestration
- Design patterns
- HLD / LLD
- Clean and maintainable code

## Tech Stack

**Backend:** Java, Spring Boot, Node.js, Express.js, REST APIs  
**Frontend:** React, Axios, Bootstrap  
**Databases:** MySQL  
**Microservices:** OpenFeign, Consul, Resilience4j  
**DevOps:** Docker, Kubernetes  
**Tools:** Swagger, JUnit, Maven, Git, GitHub

## Projects

### 1. Order & Cart Microservices ⭐

**Java | Spring Boot | MySQL | Consul | OpenFeign | Resilience4j**

Two independent microservices communicating through service discovery and REST.

**Key engineering concepts:**

- Service discovery using Consul
- Inter-service communication using OpenFeign
- Circuit breaker and fallback using Resilience4j
- REST API design
- Database persistence
- API documentation using Swagger

[View Project](...)

### 2. Rate Limiter

**Java | Spring Boot | Token Bucket | ConcurrentHashMap**

Implemented an in-memory rate limiter using the Token Bucket algorithm.

**Engineering concepts:**

- Concurrency and thread safety
- Request interception
- Token Bucket algorithm
- HLD / LLD
- Request throttling

### 3. URL Shortener

**Java | Spring Boot | REST APIs**

Designed a URL shortening service with HLD and LLD documentation.

**Engineering concepts:**

- REST API design
- URL generation and redirection
- Resource identification
- System design fundamentals

### 4. Restaurant Management System

**Java | OOP | Design Patterns**

Demonstrates the practical application of object-oriented design principles and design patterns.

**Design patterns implemented:**

- Strategy Pattern
- Observer Pattern
- Factory Pattern
- Decorator Pattern

### 5. UserSphere — Containerized Full-Stack User Management Platform

**React | Node.js | Express.js | MySQL | Docker | Kubernetes**

A full-stack user management application that implements CRUD operations through a React frontend and a Node.js/Express REST API, backed by MySQL.

The application is packaged into containers and deployed using Kubernetes manifests for local cluster orchestration.

**Key engineering concepts:**

- Full-stack application architecture
- REST API integration using Axios
- CRUD operations and relational database persistence
- Docker-based frontend and backend containerization
- Kubernetes Deployments and Services
- PersistentVolume and PersistentVolumeClaim configuration for database storage
- Service discovery and component communication within the cluster
- Environment-based database configuration
- Local deployment and container orchestration

**Architecture:**

```text
React Frontend
      |
      v
Node.js / Express REST API
      |
      v
   MySQL Database
      |
      v
 Persistent Storage

Docker + Kubernetes
manage application deployment
and container orchestration
```

**Repository:** [View Project](...)

**Note:** The Kubernetes deployment requires a configured local cluster, valid container images, and environment-specific networking and database settings.

## Architecture & System Design

Architecture diagrams and HLD/LLD documentation are included for selected projects.

The projects explore backend engineering concepts, distributed service communication, API design, database persistence, design patterns, and container orchestration.

## Author

Mayank Mishra

Software Engineer | Java | Spring Boot | Microservices
