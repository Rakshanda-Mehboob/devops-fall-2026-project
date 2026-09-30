DevOps Fall 2026 Project

A simple Hello DevOps Python application containerized using Docker as part of the DevOps course project.

Group Members
Name	ID	Section
Rakshanda Mehboob	56115	BSSE 6
Ayesha Khalil	55693	BSSE 6
Eman Idress	56964	BSSE 6
Aqsa Ahmed	53106	BSSE 6
Esha Eman	57381	BSSE 6
Project Files
hello.py – Python application
Dockerfile – Docker configuration
README.md – Project documentation
Build the Docker Image
docker build -t devops-project .
Run the Docker Container
docker run -d --name devops-container devops-project
Check Running Container
docker ps
View Output
docker logs devops-container

Expected Output

Hello DevOps



 Aqsa Ahmed - Docker Pull Test

Pulled the latest Dockerfile from the repository and pulled the group's Docker image from Docker Hub, then tested that the container runs correctly.

Commands used
docker pull rakshanda56115/devops-project:latest
docker images
docker run --name aqsa-test rakshanda56115/devops-project:latest
docker ps -a
docker rm aqsa-test

Screenshots
![docker pull](screenshots/aqsa/pull.png)
![docker images](screenshots/aqsa/images.png)
![docker run output](screenshots/aqsa/output.png)
