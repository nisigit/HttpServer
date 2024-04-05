Basic HTTP server implementation, using a TCP socket listening for incoming requests and sending back an HTTP response. This was built using C++ and CMake and is intended to run on a Docker container.

### Usage

To run the project, you need to have Docker installed on your computer. 

1. Navigate to project directory

2. Run `docker-compose build` on your terminal to build the docker image.
3. Start the server by running `docker-compose up`
4. Visit `localhost:8080` on your browser to connect to the server. The project can also be modified to run on other ports.
5. To stop the container, simply press `CTRL+C` on the same terminal or navigate to the project directory on a new terminal and run `docker-compose down`.


