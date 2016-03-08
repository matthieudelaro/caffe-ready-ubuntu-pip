# caffe-ready-ubuntu-pip
Dockerfile to build an image of Ubuntu + caffe dependencies

Inspired by image tleyden5iwx/caffe-gpu-master : https://hub.docker.com/r/tleyden5iwx/ubuntu-cuda

Run me with proper parameters:
nvidia-docker run -i -t --device=/dev/nvidia0:/dev/nvidia0 --device=/dev/nvidiactl:/dev/nvidiactl matthieudelaro/caffe-ready-ubuntu-pip

Your devices may change depending on your hardware. Use those returned by:
ls /dev | grep nvidia
