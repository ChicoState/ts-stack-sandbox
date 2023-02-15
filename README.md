# Sandbox for experimenting in a TypeScript stack

1. To get started, clone this repository locally.
2. Build the Docker image using: `docker build -t ts-sandbox .`
3. Run the detached container with port 8080: `docker run -p 8080:8080 -d ts-sandbox`
4. View the server's response at [0.0.0.0:8080](http://0.0.0.0:8080)

## Launching with database

1. First, confirm that your web server builds and runs successfully (above) and stop the container
2. Build the *server with a corresponding database* using: `docker-compose build`
3. After that completes, run the containers together: `docker-compose up`
4. View the server's response at [0.0.0.0:8080](http://0.0.0.0:8080)