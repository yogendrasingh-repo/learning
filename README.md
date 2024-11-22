# Spring Config Server example Project

This project demonstrates the implementation of a Spring Cloud Config Server to manage the external configuration for distributed systems.

## Features

- Centralized external configuration management
- Support for multiple environments (e.g., `dev`, `test`, `prod`) based on the profile
- Integration with Git for version-controlled configuration
- Dynamic property updates for client applications using Spring Cloud Bus

## Prerequisites

- **Java**: JDK 17 or higher
- **Spring Boot**: 3.x or higher
- **Maven**: 3.8 or higher
- **Git**: Configurations are managed in a Git repository

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-repo/spring-config-server.git
cd spring-config-server
