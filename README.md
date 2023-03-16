# ROS Docker Development Setup
## Setup
- [install docker](ttps://docs.docker.com/get-docker/)
- clone this repo with `git clone git@github.com:hoenigpeter/ros_docker.git` 
- use `bash download_example_projects.sh` to download some ROS Noetic examples packages into the `./projects` folder
- use `docker compose up` to build and run the docker container
- to open a new shell of the ROS docker container use `docker exec -it ros_docker-master-1 /bin/bash`
- you can now use this shell like with a native ROS installation
- start by building the workspace again with `catkin_make`
- add other ROS noetic packages in the `./projects` folder for development
