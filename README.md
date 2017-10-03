# Vertex Java Example
Creates a simple web server and performs an echo function. 
Docker file uses the maven image and runs.

## Docker commands
- docker build -t gordonbmsft/vertex .
- docker run --name vertex -p 8080:8430 --rm -i -t gordonbmsft/vertex
- docker push gordonbmsft/vertex
