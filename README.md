# ml-docker
Docker file for ML with GPU enabled

## build docker image

```
git clone https://github.com/deyuhua/ml-docker.git
cd ml-docker
docker build -t ml-gpu-enalbed .
```

## usage

```
docker run -it -v path_on_your_system:path_on_docker_system ml-gpu-enabled
cd path_on_docker_system
jupyter-notebook
```

open lcoalhost:8888 with your favorite browser.

## notes

This docker image file only work on linux system with GPU device driver installed already!
