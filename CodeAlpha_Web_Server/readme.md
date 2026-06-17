# Web Server using Docker

## Project Overview

This project is developed as part of the CodeAlpha Internship and focuses on deploying a web server using Docker containerization technology. The project demonstrates how Docker can be used to create, configure, and run a lightweight and portable web server environment.

The main objective of this project is to understand containerization concepts and learn how web applications can be deployed efficiently using Docker.

## About Docker

Docker is a containerization platform that allows developers to package applications and their dependencies into isolated containers. Containers provide a consistent environment for running applications across different systems.

In this project, Docker is used to create a web server container that hosts and serves web content efficiently.

## Features

* Containerized web server deployment
* Lightweight and portable environment
* Easy application setup and management
* Isolated server environment
* Efficient resource utilization
* Simple deployment process
* Consistent execution across systems

## Technologies Used

* Docker
* Docker Image
* Docker Container
* Web Server (Apache / Nginx)
* HTML
* CSS
* JavaScript
* GitHub

## Project Structure

Web-Server-Docker

* website

  * index.html
  * style.css
  * script.js

* Dockerfile

* README.md

* screenshots

## Working of the Application

The web server application is packaged inside a Docker container using a Dockerfile. The Docker image contains all required configurations and dependencies needed to run the server.

When the Docker container is started, the web server runs inside the isolated environment and serves the website files to users through the assigned port.

The browser communicates with the Docker container through the web server, allowing users to access the hosted application.

## Docker Commands Used

### Build Docker Image

```
docker build -t web-server .
```

This command creates a Docker image from the Dockerfile.

### Run Docker Container

```
docker run -p 8080:80 web-server
```

This command starts the container and maps the server port.

### View Running Containers

```
docker ps
```

This command displays active Docker containers.

### Stop Container

```
docker stop container_id
```

This command stops the running container.

## Dockerfile Configuration

The Dockerfile defines the environment required to run the web server. It specifies the base image, application files, and server configuration needed to create the container.

Example workflow:

1. Select a web server base image.
2. Copy website files into the container.
3. Expose the required port.
4. Start the web server.

## How to Run the Project

1. Download or clone the repository.
2. Install Docker on your system.
3. Open the project folder in the terminal.
4. Build the Docker image:

```
docker build -t web-server .
```

5. Run the Docker container:

```
docker run -p 8080:80 web-server
```

6. Open the browser and visit:

```
http://localhost:8080
```

7. View the hosted website.

## Learning Outcomes

Through this project, I learned:

* Fundamentals of Docker containerization
* Creating and managing Docker images
* Running applications inside containers
* Deploying web servers using Docker
* Understanding container-based application deployment
* Improving knowledge of DevOps practices

## Future Enhancements

* Deploy Docker containers on cloud platforms
* Add Docker Compose for multi-container applications
* Implement HTTPS support
* Add automated CI/CD deployment
* Monitor container performance
* Use Kubernetes for container orchestration

## Author

Mitushi Jain

## Internship Program

CodeAlpha Web Server using Docker Internship

## License

This project is created for educational and internship purposes.

