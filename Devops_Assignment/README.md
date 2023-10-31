# Dockerizing WordPress with Dockerfile, Docker Compose, and Database Optimization.
## Table of Contents
##### 1.	Objective
##### 2.	Dockerizing WordPress
##### 3.	Instructions for Building and Running

## 1. Objective:
 The project's goals are to optimise the database for performance and Dockerize a WordPress application. Using Docker Compose, you may build and execute the WordPress application that has been Dockerized. Detailed steps are provided below.

 ## 2. Dockerizing WordPress:
 ### Dockerfile:
 
 I used the official WordPress image as the basis image to create a Dockerfile for the WordPress application. Environment variables are used to safely manage sensitive data, such as database credentials.

 ### Docker Compose:

• Create a Docker Compose file (docker-compose.yml) to coordinate the WordPress application and its database (MySQL or MariaDB).

• Network configurations and service dependencies.

• Securely managed configuration parameters using environment variables.

## 3. Instructions for Building and Running:

1. Clone this repository to your personal computer.
2. Go to the project directory by navigating.
3. Execute or run the command to build and start the containers:
   
   ```
   docker-compose up -d
   ```
4. Use your web browser to access the WordPress website at http://localhost:8000 (or the relevant port if adjusted).
   


