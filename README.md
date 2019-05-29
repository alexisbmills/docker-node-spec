# docker-node-spec
Docker image for running code coverage on NodeJS applications

## Updating image

Basic steps making updates to the image:
1. Update image
2. Build image
    ```
    $ docker build -t docker-node-spec:latest .
    ```
3. Tag and push
    ```
    $ docker tag docker-node-spec:latest alexisbmills/docker-node-spec:latest
    $ docker push alexisbmills/docker-node-spec:latest
    ``` 