# DevOps Fall 2026 Project

A simple **Hello DevOps** Python application containerized using **Docker** as part of the DevOps Fall 2026 course project.

## Group Members

| Name              | ID    | Section |
| ----------------- | ----- | ------- |
| Rakshanda Mehboob | 56115 | BSSE-6  |
| Ayesha Khalil     | 55693 | BSSE-6  |
| Eman Idrees       | 56964 | BSSE-6  |
| Aqsa Ahmed        | 53106 | BSSE-6  |
| Esha Eman         | 57381 | BSSE-6  |

## Project Structure

```text
.
├── hello.py
├── Dockerfile
├── docker-compose.yml
└── README.md
```

## Build the Docker Image

```bash
docker build -t devops-project .
```

## Run the Container

```bash
docker run -d --name devops-container devops-project
```

## Using Docker Compose

Build the services:

```bash
docker compose build
```

Start the services:

```bash
docker compose up -d
```

Stop the services:

```bash
docker compose down
```

## Verify the Container

```bash
docker ps
```

## View Logs

```bash
docker logs devops-container
```

## Expected Output

```text
Hello DevOps
```
