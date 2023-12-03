# Popeye 📦

Welcome to **Popeye**.

A project designed for an immersive introduction to DevOps, particularly in Docker and containerization.

Like Popeye confidently sails across the seas, in this project, you'll learn to navigate the vast world of operating systems and configurations with containers.

## Introduction to DevOps 🧭

This project is part of Introduction to DevOps, focusing on mastering the basics of containerizing applications and describing multi-container infrastructures using Docker and Docker Compose.

## Project Overview 🔎

- **Understanding Docker**: Learn about one of the most popular containerization software today.
- **Containerization**: Package applications and their runtime environments efficiently.
- **Docker Compose**: Master the art of describing and managing multi-container infrastructures.
- **Practical Application**: Implement a functioning system comprising various interconnected containers.

### Project Structure

Ensure your project repository contains the following files and directories:

```
.
|-- docker -compose.yml
|-- schema.sql
|-- poll
|   |-- Dockerfile
|-- result
|   |-- Dockerfile
`-- worker
    |-- Dockerfile
```


`poll`, `result`, and `worker` are directories containing the applications provided on the intranet.

### Key Features

- **Network Configuration**: Set up 3 networks for inter-service communication.
- **Persistent Storage**: Utilize named volumes for database persistence.
- **Service Orchestration**: Correctly sequence the launching of services, ensuring dependencies are met.
- **Automated Recovery**: Ensure containers restart automatically after unexpected stops.
- **Environment Variables**: Manage environment variables effectively within `docker-compose.yml`.

## Technical Requirements 🛠️

- **Docker and Docker Compose**: Utilize these tools for containerization and orchestration.
- **Automated Tests**: Your project will be evaluated based on configuration files like Dockerfiles and `docker-compose.yml`.
- **File Organization**: Maintain a clean repository, excluding unnecessary files (binaries, temp files, object files, etc.).

## Installation and Usage 💾

1. Clone the repository.
2. Run the program: `docker-compose up`.
3. For detailed guidelines, refer to `popeye.pdf`.

This command will launch all the services.

You can then observe the functionalities, such as submitting votes on the poll's webpage and viewing them on the result's webpage.

## License ⚖️

This project is released under the MIT License. See `LICENSE` for more details.
