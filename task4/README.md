# Docker Containerization

This project demonstrates containerizing a Node.js application using Docker.

## Objectives

- Understand containerization concepts
- Write a Dockerfile using best practices
- Use minimal base image (Alpine)
- Apply layer caching optimization
- Run a container in detached mode with port mapping

## Technologies Used

- Node.js
- Express
- Docker

## Project Structure

```
app/
├── index.js
├── package.json
├── Dockerfile
└── .dockerignore
```

## Build & Run

```bash
docker build -t my-app:v1 .
docker run -d -p 8080:80 my-app:v1
```

## Result

Container runs in the background, accessible at `http://localhost:8080`

## Author

Abdrahman Walied Nasr
