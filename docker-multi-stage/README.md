# Multi Stage Docker build example
'Dockerfile' contains various stages which are tagged by a name using 'as'.

## Commands used
- 'docker build . -t docker-multi-stage:v1' - Build image
- 'docker build . -t docker-multi-stage:v1 --target=builder' - Build image using a specific stage
- 'docker run docker-multi-stage:v1 -p 8080:8080' - Run image