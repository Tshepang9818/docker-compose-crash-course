This Docker Compose application sets up a development environment for a MongoDB-based project. It consists of three services:

1. my-app: A custom application built from the current directory, exposing port 3000.
2. mongodb: A MongoDB database service, exposing port 27017.
3. mongo-express: A MongoDB administration interface, exposing port 8081.

Purpose
This application is designed to provide a local development environment for a MongoDB-based project, allowing developers to easily spin up and manage the required services.

Features
- Easy setup and teardown of MongoDB and mongo-express services
- Environment variable-driven configuration for MongoDB credentials
- Custom application service with exposed port 3000
