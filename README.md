# gs-boot-docker

Build a multi-stage image to build and run the project(https://github.com/spring-guides/gs-spring-boot.git). 
## pre Requirement
- Docker ```sudo apt install docker.io```


## Run 

Clone the project

```bash
  git clone https://github.com/waheeb96/gs-boot
```

```bash
  cd gs-boot
```

Build

```bash
  docker build -t gs-boot .
```

Run

```bash
  docker run -d -p 8080:8080 gs-boot
```


## DockerHub

Run the image from DockerHub

![docker-pic-1](https://user-images.githubusercontent.com/72220299/177042111-cdc3a662-364d-46f3-9738-3961cf1139f4.PNG)

