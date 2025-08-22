[DOCKER HUB LINK]("https://hub.docker.com/repository/docker/gosyav/todoapp/general")

## Build & Run
```
docker build -t todoapp .
docker run --name todoapp -d -p 8080:8080 todoapp
```

Go to ["http://localhost:8080"](http://localhost:8080) to access the application