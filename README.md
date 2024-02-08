Estudiamos [**esto**](https://www.docker.com/blog/getting-started-with-docker-using-node-jspart-i/)

## Build image:
    `docker build --tag node-docker .`

## Run container:

- Daemon mode:
  - `docker run --publish 8000:8000 node-docker` 
  - **no** simplemente: `docker run node-docker`

- Detached mode:
  - `docker run -d -p 8000:8000 node-docker`
- 