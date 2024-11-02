# rank-anything
Build the container for Apache Nutch 
docker build -t apache/nutch . --build-arg BUILD_MODE=2 --build-arg SERVER_PORT=8081 --build-arg SERVER_HOST=0.0.0.0 --build-arg WEBAPP_PORT=8080
