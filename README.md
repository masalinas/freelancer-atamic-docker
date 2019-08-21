# description
Freelancer Atamic Semaphore Python Docker

# list images
```
docker images
```

# list containers
```
docker container ls -a
```

# remove containers from ID
```
docker container rm <CONTAINR_ID>
```

# remove images from tag
```
docker rmi atamic-python:latest
```

# build images
```
docker build -t atamic-python .
```

# tag latest docker images
```
docker tag <IMAGE_ID> atamic-python:3.7.4
```

# execute a docker image with interactive shell
```
docker run -i -t atamic-python:3.7.4 /bin/bash
```

# tag image to
```
docker tag <IMAGE_ID> <DOCKER_HUB_ID>/atamic-python:latest
```

# push image to docjer GitHub
```
docker login
docker push <DOCKER_HUB_ID>/atamic-python:latest
```

# copy any file from local to docker container
```
docker cp <FILE> <CONTAINER_ID>:/root
```
