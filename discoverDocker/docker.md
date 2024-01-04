# Writing a Dockerfile

A docker file is a text file with a series of commands in it

# Building a Docker image

docker command to build an image


```docker
docker build .
```

# Running a Docker Container

```
docker run -i -t -p 8000:8000 --name example1 todpapp

```
docker command to see containers that have been started and removed

```
docker ps -a
```

# Docker Layering

Docker uses a copy-on-write mechanism to reduce the amount of disk space.

When a container needs to write to a file, it records the chane by copying the item to a new area of disk

