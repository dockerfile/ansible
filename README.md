## Ansible Dockerfile


This repository contains **Dockerfile** of [Ansible](http://www.ansible.com/) for [Docker](https://www.docker.io/)'s [trusted build](https://index.docker.io/u/dockerfile/ansible/) published to the public [Docker Registry](https://index.docker.io/).


### Dependencies

* [dockerfile/python](http://dockerfile.github.io/#/python)


### Installation

1. Install [Docker](https://www.docker.io/).

2. Download [trusted build](https://index.docker.io/u/dockerfile/ansible/) from public [Docker Registry](https://index.docker.io/): `docker pull dockerfile/ansible`

   (alternatively, you can build an image from Dockerfile: `docker build -t="dockerfile/ansible" github.com/dockerfile/ansible`)


### Usage

    docker run -it --rm dockerfile/ansible
