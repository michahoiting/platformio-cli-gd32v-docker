# Build environment for using PlatformIO Core (CLI) projects.

Contains the complete installation of PlatformIO Core (CLI) for working with RISC-V GD32V based boards (e.g. GD32VF104C-START and Sipeed Longan Nano).

## Installation

1. Install [Docker](https://www.docker.com/)

2. Pull the image directly from DockerHub:

```sh
docker pull mhoiting/platformio-cli-gd32v
```

## Usage

Ideally use this container within a CI/CD pipeline of your choice.

Alternatively, you could use it interactively: `docker run -it -v <host_dir>:<container_dir> mhoiting/platformio-cli-gd32v /bin/bash`.

## Build

Building the image yourself is also possible, via:

```sh
docker build --tag mhoiting/platformio-cli-gd32v .
```
