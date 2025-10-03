Description 
  This project demonstrates how to build a multi-container application using Docker Compose.
It includes: 
- A Frontend container running HTTPD (Apache) that displays my name in the browser. 
- A Backend container running Flask (using image: ranaahmed2/flask-app:0.1).
- A Databasecontainer running MariaDB with a configured root password.
- The containers are connected using two custom networks (frontend and backend) to simulate a real-world microservices architecture.
Requirements
  • Docker
  • Docker Compose
Setup & Usage
  • Clone the repository: git clone https://github.com/username/repository.git cd repository
  • Start the containers: docker-compose up -d
  • Access the application: Open browser at http://localhost:8080
Project Structure
  • docker-compose.yml → Defines all services, networks, and dependencies.
  • frontend/ → HTML file that shows my name.
  • backend/ → Flask application.
  • database/ → MariaDB container with environment variables
Networks
  • frontend network → connects frontend ↔ backend.
  • backend network → connects backend ↔ database.
  
