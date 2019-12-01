# docker
The project is for storing the docker files used for homebrew projects

The PyTorch Dockerfiles can also be used as installation guides for Anaconda. All installation commands work in an Anaconda virtual environment.

## Often used Docker commands
    $ Docker images
    $ Docker build -t <repository:tag_name>
    $ Docker volume create --name <volume_name>
    $ Docker volume ls
    $ Docker ps
    $ Docker stop <image_name/id>
    $ winpty docker exec -t -i <container_id> sh (on Windows)
    $ docker exec -t -i <container_id> /bin/bash (on Linux)
