# Transmission with python

Transmission docker container with python, (also unrar, and a few extra python modules)

This docker container uses [dperson/transmission](https://github.com/dperson/transmission) image as a base image and adds python. Mainly because I want to run a python script when torrents complete.

For instructions on how to run this contianer see [dperson/transmission](https://github.com/dperson/transmission).
Also credit to [Docker-Hub-frolvlad/docker-alpine-python3](https://github.com/Docker-Hub-frolvlad/docker-alpine-python3/), where I took the instructions to install python in alpine.
Baically it's just a merge of these 2 images.
