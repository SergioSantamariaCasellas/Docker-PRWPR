# Docker Compose Execution Guide

Follow the steps below to execute and test your Docker Compose setup.

---

## Steps for Execution

### 1. Build the Containers
Run the following command to build the containers:
docker-compose build

### 2. Start the Containers
Start all services defined in your `docker-compose.yml` file:
docker-compose up

---

## Steps for Testing

### 1. Poll Page
Access the poll page at:
http://localhost:5000

### 2. Result Page
Access the result page at:
http://localhost:5001

---

## Stop and Clean Up

To stop and remove all containers, networks, volumes, and images created by `docker-compose up`, run:
docker-compose down

---

## Notes
- Ensure your `docker-compose.yml` file is properly configured before running these commands.
- The URLs assume default ports; update them if your configuration uses different port mappings.

Happy containerizing!
