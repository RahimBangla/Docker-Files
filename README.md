# Docker-Files
All Docker Files Sample here


Step 3: Define services in a Compose file🔗
Create a file called docker-compose.yml in your project directory and paste the following:

version: "3.8"
services:
  web:
    build: .
    ports:
      - "5000:5000"
  redis:
    image: "redis:alpine"
This Compose file defines two services: web and redis.
