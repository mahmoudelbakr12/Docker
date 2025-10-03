# System Tool

## Description
 This project demonstrates how to build a multi-container application using Docker Compose.

## Requirements
-  Docker 
-  Docker Compose 

## Setup & Usage
1. Clone the repository: git clone https://github.com/username/repository.git cd repository
2. Start the containers: docker compose up -d
3.  Access the application: Open browser at http://localhost:8080


##  Project Structure

1. docker-compose.yml → Defines all services, networks, and dependencies.
2. frontend/ → HTML file that shows my name.
3. backend/ → Flask application.
4. database/ → MariaDB container with environment variables.

## Networks
- frontend network → connects frontend ↔ backend.
- backend network → connects backend ↔ database.
## Dependencies
-  Backend depends on Database.
-  Frontend depends on Backend.

