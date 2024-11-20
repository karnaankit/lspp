# Project Setup

## Environment Setup

1. Create a `.env` file in the root directory of the project.
2. Copy the contents of `.env.example` into the newly created `.env` file.
3. Fill in the necessary environment variables in the `.env` file.

## Using Docker Compose

To get started with Docker Compose, follow these steps:

1. Make sure you have Docker and Docker Compose installed on your machine.
2. Run the following command to start the services:

    ```sh
    docker-compose up -d --build
    ```

This command will build and start the containers defined in the `docker-compose.yml` file.

## Accessing the Application

Once the containers are up and running, you can access the application at `http://localhost:80`.

## Stopping the Services

To stop the services, run:

```sh
docker-compose down