# Docker Walkthrough

## Description
A walkthrough of how to package, build, run, tag and push a docker image 
## Pre-Requisites
* Have docker installed
* Create a repository on docker hub named python-helloworld 

# Build Image
* docker build -t python-helloworld .

# List Image
* docker images

# Run Image
* docker run -d -p 5000:5000 python-helloworld

# List Running Containers
* docker ps

# Tag Image
* docker tag python-helloworld 'your docker hub username'/python-helloworld:v1.0.0

# Docker Login
* docker login

# Push Image
docker push 'your docker hub username'/python-helloworld:v1.0.0

