# initial-golang-project
Start golang development with less command
### pre-requirement
- docker
- terminal ( able to run the docker )

### Firster time build live reload image and initial go module

you can change
- golang image inside file `Dockerfile-DEV` at FROM `golang:1.16beta1-alpine3.13`
- project name inside the command go mod init `initial-golang-project`
```
docker-compose build && \
docker-compose run --entrypoint "go mod init initial-golang-project" app
```

### When develop
```
docker-compose up
```
Let's start 

## VS Code
can debug in container by ... to be continue