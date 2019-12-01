# docker
The project is for storing the docker files used for homebrew projects

The PyTorch Dockerfiles can also be used as installation guides for configuring a PyTorch virtual environment in Anaconda. All installation commands work in an Anaconda virtual environment.

Note that PyTorch GPU Dockerfile requires a Linux host with Nvidia GUDA driver installed. I only have an Ubuntu running as Windows Subsystem at the moment, so the GPU Dockerfile cannot be tested. If anyone can test it, please feel free to update the README.

## Often used Docker commands
    $ Docker images
    $ Docker build -t <repository:tag_name>
    $ Docker volume create --name <volume_name>
    $ Docker volume ls
    $ Docker ps
    $ Docker stop <image_name/id>
    $ winpty docker exec -t -i <container_id> sh (on Windows)
    $ docker exec -t -i <container_id> /bin/bash (on Linux)
