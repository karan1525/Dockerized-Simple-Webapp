# My Simple Webapp

### Run a Dockerized version of the My Simple Webapp on a Docker container

#### This repo includes the directory structure and the Dockerfile to run/ build the Simple Webapp

##### How to run these Docker files:

```sh
$ docker pull kbhargava/my-simple-webapp
$ docker run -p 8080:8080 --rm kbhargava/my-simple-webapp
```

Verify the deployment by navigating to your server address in your preferred browser.

```sh
localhost:8080
```
