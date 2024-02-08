estudiamos [**esto**](https://www.docker.com/blog/getting-started-with-docker-using-node-jspart-i/)



run container:

    daemon mode:
        `docker run --publish 8000:8000 node-docker` 
        # **no** asi: `docker run node-docker`

    detached mode:
        `docker run -d -p 8000:8000 node-docker`