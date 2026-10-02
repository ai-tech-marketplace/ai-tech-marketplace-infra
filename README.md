# AI Tech Marketplace — Infrastructure

Infrastructure configuration for AI Tech Marketplace.

## Technology

* Docker
* Docker Compose
* PostgreSQL
* Redis
* Kafka
* Nginx
* Monitoring

## Responsibilities

This repository contains infrastructure configuration required to run the marketplace locally and eventually in production.

## Local Architecture

```text
React
  |
  v
Nginx
  |
  v
Spring Boot
  |
  ├── PostgreSQL
  ├── Redis
  └── Kafka

Spring Boot
  |
  v
Python AI Service
```

## Development

Docker Compose configuration will be added during the infrastructure phase.
