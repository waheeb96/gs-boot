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

```bash
  docker pull mohamadassi173/gs-boot:latest
  docker run -d -p 8080:8080 mohamadassi173/gs-boot:latest
```
