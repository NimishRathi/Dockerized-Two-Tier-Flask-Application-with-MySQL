# Dockerized-Two-Tier-Flask-Application-with-MySQL
This project demonstrates the deployment of a scalable and efficient two-tier web application using Docker. It utilizes Docker build, images, containers, and networking to seamlessly integrate a Flask frontend with a MySQL backend.

### Project Overview
In this project, we have containerized a two-tier web application consisting of a Flask frontend and a MySQL backend. The Flask application serves as the frontend, handling user requests and interactions, while the MySQL database stores and manages the application's data.

### Key Concepts Demonstrated
**Docker Build, Images, Containers:** Docker is used to containerize both the Flask application and the MySQL database. Docker images are created for each component, ensuring consistency and portability across different environments. These images are then instantiated as containers, providing isolated execution environments for the application components.

**Docker Networking:** Docker networking facilitates communication between the Flask frontend and the MySQL backend. By connecting both containers to the same user-defined Docker network, we enable seamless interaction between the application tiers. This networking setup ensures efficient data exchange and enhances application scalability.

### Docker Configuration
**Dockerfile for Flask App**
The Dockerfile for the Flask application sets up a Python environment, installs dependencies, and copies the Flask app code into the container.
