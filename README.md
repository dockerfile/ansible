## Ansible Dockerfile


This repository contains **Dockerfile** of [Ansible](http://www.ansible.com/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/dockerfile/ansible/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).


### Base Docker Image

* [dockerfile/python](http://dockerfile.github.io/#/python)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/dockerfile/ansible/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull dockerfile/ansible`

   (alternatively, you can build an image from Dockerfile: `docker build -t="dockerfile/ansible" github.com/dockerfile/ansible`)


### Usage

    docker run -it --rm dockerfile/ansible
