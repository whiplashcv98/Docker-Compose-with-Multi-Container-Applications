# Docker-Compose-with-Multi-Container-Applications
This project demonstrates how to build and run a multi-container application using Docker Compose. The application consists of a Python Flask web server and a Redis database, which are designed to work together in a containerized environment.This project helped us understand how to run multiple services, link them, and test that they work in a clear and practical way.
Project Objectives
Containerize a Python Flask application using Docker.

Use Redis as a database for data storage and retrieval.

Link multiple services using Docker Compose.

Test connectivity between services.

Task 1: Create a Project Directory
We created a directory named Group5 to hold all our project files, including app.py, requirements.txt, Dockerfile, and docker-compose.yml.

Task 2: Write a Dockerfile
A Dockerfile was written to define the environment for the Flask application. This file specifies the base image, installs dependencies, and defines the application's entry point.

Task 3: Write a docker-compose.yml File
We wrote a docker-compose.yml file to define and link the two services: a Flask web app and a Redis database. This file orchestrates the containers, allowing them to communicate with each other.

Task 4: Run and Test
We ran the multi-container application using the docker-compose up --build command. This command built the images, created the containers, and started the application.

Challenges
Build Path Issues: A subfolder was created and the Dockerfile was placed inside, causing initial build path problems.

Missing Python Dependencies: Python was not initially installed, and the requests library needed to be installed to run a populate.py script successfully.

Connection Issues: Connection issues occurred when Redis was not recognized until the correct host and environment setup were used.

Conclusion
This project provided hands-on experience in building a simple web application and connecting it to a database using containers. We practiced using Docker, Docker Compose, and basic Flask app development, which are essential skills for larger cloud and container-based deployments.
