# Geography App

This is a simple example of a client-server application using Docker Compose, with the client and API services.

## Prerequisites

- Docker: [Install Docker](https://docs.docker.com/get-docker/)

## How to Run

### In  your terminal:

1. Clone the repository:

   ```bash
   git clone https://github.com/pockche123/geography-game.git
   cd geography-app
   ```

2. Build and start the Docker containers: 
   ```bash
    docker compose up
    ```

   This command will download the required Docker images, build the containers, and start the services.

3. Open your web browser and access the client at http://127.0.0.1:8080


### API Service
4. The API service is a Node.js application that runs on port 3000.URL: http://localhost:3000


## Stopping the Application
To stop the application and shut down the Docker containers, use:

```bash
   docker compose down
   ```



