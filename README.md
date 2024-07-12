# Docker-Commands

`docker run -it --entrypoint /bin/bash --gpus all --rm --network=host -v /home/tensorgo/foot_fall_django:/opt/nvidia/deepstream/deepstream-7.0/code -v /tmp/.X11-unix/:/tmp/.X11-unix --privileged -v /var/run/docker.sock:/var/run/docker.sock -e NVIDIA_VISIBLE_DEVICES=all -e NVIDIA_DRIVER_CAPABILITIES=all nvcr.io/nvidia/deepstream:7.0-gc-triton-devel`
