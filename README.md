
# Rank-Anything

Rank-Anything is a tool to gather data and rank all the saerch results based on the gathered data. eg - presidents of india - should rank them.


## Table of Contents

- [Build the Docker Container](#build-the-docker-container)
- [Running the Container](#running-the-container)

---

## Build the Docker Container

To build the Docker container for Apache Nutch, use the following command:

```bash
docker build -t apache/nutch . --build-arg BUILD_MODE=2 --build-arg SERVER_PORT=8081 --build-arg SERVER_HOST=0.0.0.0 --build-arg WEBAPP_PORT=8080
```

---

## Running the Container

Run the container with the following command:

```bash
docker run -it -p 8081:8081 -p 8080:8080 <container id>
```


---

