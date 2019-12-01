# docker
The project is for storing the docker files used for my homebrew projects

The PyTorch Dockerfiles can also be used as installation guides for configuring a PyTorch virtual environment in Anaconda. All installation commands work in an Anaconda virtual environment.

Note that PyTorch GPU Dockerfile requires a Linux host with Nvidia CUDA driver installed. I only have an Ubuntu running as Windows Subsystem at the moment, so the GPU Dockerfile cannot be tested. If anyone can test it, please feel free to update the README.

However, if you install all the dependencies manually in an Anaconda environment on a Windows host with Nvidia CUDA driver, the environment works fine with GPU.

## Often used Docker commands
    $ docker images
    $ docker build -t <repository:tag_name>
    $ docker volume create --name <volume_name>
    $ docker volume ls
    $ docker ps
    $ docker stop <image_name/id>
    $ winpty docker exec -t -i <container_id> sh (on Windows)
    $ docker exec -t -i <container_id> /bin/bash (on Linux)
