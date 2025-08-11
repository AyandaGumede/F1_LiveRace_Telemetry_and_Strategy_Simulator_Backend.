# F1 Live Race Telemetry & Strategy Simulator - Backend

This repository contains the backend services for the **F1 Live Race Telemetry & Strategy Simulator** project.

Built with **Spring Boot** (multi-module Maven project), it consists of:

- **api-gateway**: Handles authentication, routing, and security using Spring Security and JWT.
- **telemetry-service**: Simulates and streams real-time race telemetry data via WebSocket.
- **strategy-service**: Runs the pit stop prediction algorithms and exposes REST endpoints.
- **data-service**: Manages persistent storage of race data using PostgreSQL and InfluxDB.

The backend exposes REST APIs and WebSocket endpoints consumed by the Angular frontend. It’s designed for scalability and modularity, leveraging Docker and Docker Compose for local development.


### Key Features

- Real-time telemetry data streaming with WebSocket.
- Pit stop strategy prediction engine.
- Historical race data storage and replay support.
- Secure JWT-based authentication and authorization.


Backend:

Spring Boot (Java 21+)

WebSocket + REST controllers

Spring Data JPA (PostgreSQL)

InfluxDB Java client

Redis (Spring Data Redis) for caching

Spring Security (JWT)

DevOps & Tooling:

Docker & Docker Compose (local dev)

GitHub Actions (CI/CD)

Terraform (optional, infra provisioning)

Kubernetes (Minikube for local, cloud for deploy)

Prometheus + Grafana (monitoring)

JUnit + Testcontainers (testing)
