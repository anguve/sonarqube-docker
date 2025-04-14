# SonarQube with PostgreSQL - Docker Setup

This repository provides a simple Docker Compose setup to run **SonarQube (Community Edition)** with a **PostgreSQL** database.

## Prerequisites

Before you start, make sure you have the following installed:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Configuration

### Environment Variables

You must create a `.env` file in the root directory with the following variables:

```env
SONARQUBE_JDBC_USERNAME=sonar
SONARQUBE_JDBC_PASSWORD=yourStrongPassword
```
