# Docker Compose Application Setups

This repository contains various Docker Compose configurations for different applications. Each sub-folder represents a separate setup for dockerizing applications using Docker Compose.

## Table of Contents
- [Setup List](#setup-list)
- [How to Use](#how-to-use)
- [Folder Details](#folder-details)
- [License](#license)

## Setup List

1. **mysql-wordpress** - Docker Compose setup for running a WordPress website with a MySQL database.
2. **docker-compose-data** - Example configuration for Docker Compose volumes and persistent data management.
3. **Flask-redis** - Flask application with Redis as a caching mechanism using Docker Compose.
4. **nginx_proxy-flask-mongo** - Nginx reverse proxy for a Flask application with MongoDB as the database.
5. **nginx-nodejs-redis-loadbalancer** - `Node.js` application with Redis for session storage and Nginx as a load balancer.
6. **spring-java-postgres** - Spring Boot Java application with PostgreSQL database using Docker Compose.
7. **elasticsearch-logstash-kibana** - The ELK stack setup for log management with Elasticsearch, Logstash, and Kibana.
8. **prometheus-grafana** - Monitoring and alerting setup using Prometheus with Grafana as a visual dashboard.

## How to Use

1. **Clone the repository**:
   ```bash
   git clone <your-repo-url>
   cd <your-repo-directory>
   ```

2. **Navigate to the desired setup:** Each sub-folder contains a specific Docker Compose configuration. Navigate to the folder of your choice, for example:
   ```bash
   cd mysql-wordpress
   ```

3. Run the setup: Each setup contains a `docker-compose.yml` file. To start the services, use:
   ```bash
   docker-compose up -d
   ```

4. Stop the setup: To stop the services, run:
   ```bash
   docker-compose down
   ```

## Folder Details
1. **mysql-wordpress:** 
   - This setup provides a basic WordPress website with MySQL as the backend database.

2. **docker-compose-data:** 
   - An example to demonstrate persistent data management with Docker volumes using Docker Compose.

3. **Flask-redis:** 
   - A simple Python Flask web application connected to a Redis server for caching data.

4. **nginx_proxy-flask-mongo:** 
   - An Nginx reverse proxy setup with a Flask web application and MongoDB database for data storage.

5. **nginx-nodejs-redis-loadbalancer:** 
   - A Node.js application with Redis for session management, and Nginx acting as a load balancer for improved scalability.

6. **spring-java-postgres:** 
   - A Spring Boot Java application connected to a PostgreSQL database.

7. **elasticsearch-logstash-kibana*:** 
   - The ELK stack (Elasticsearch, Logstash, and Kibana) configured for log management and analysis.

8. **prometheus-grafana:** 
   - A monitoring and alerting setup using Prometheus as a metrics collector and Grafana for visualizing the metrics data.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute these setups for your own needs.