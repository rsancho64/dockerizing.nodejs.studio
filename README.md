- Estudiamos [**esto**](https://www.docker.com/blog/getting-started-with-docker-using-node-jspart-i/)
- Actualización (2024) [**aqui**](https://www.digitalocean.com/community/tutorials/how-to-build-a-node-js-application-with-docker)

## Build image:
    `docker build --tag node-docker .`

## Run container:

- Daemon mode:
  - `docker run --publish 8000:8000 node-docker` 
  - **no** simplemente: `docker run node-docker`

- Detached mode:
  - `docker run -d -p 8000:8000 node-docker`
- 
