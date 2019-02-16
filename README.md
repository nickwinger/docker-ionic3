# docker-ionic3
Docker image to build ionic3 android

This is a fork of https://hub.docker.com/r/marcomaisel/ionic/
Difference is that i use node 8 instead of 10, because the level-down version in my Ionic3 Dependencies
don't work with node 10

- Ionic 3
- Cordova
- node 8 & npm
- Java
- Android SDK
- Gradle
- Docker Garbage Collection to remove Containers that exited more than an hour ago

----

### Pull from Docker Hub
```
docker pull thebit4bit/ionic3:v1.0.0
```

### Build from GitHub Repository
```
docker build -t thebit4bit/ionic3:v1.0.0 github.com/nickwinger/docker-ionic3
```

### Run image
```
docker run -it thebit4bit/ionic3:v1.0.0
```

### Use as base image
```Dockerfile
FROM thebit4bit/ionic3:v1.0.0
```

-----

### Fork of
https://github.com/marcomaisel/docker-ionic
