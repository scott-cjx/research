# Docker RP2040 C/C++ SDK
this will serve as a guide to compile pico-sdk using Docker.

## Getting Started

This environment has only been tested on MacOS. Your mileage may vary.

1. Install [Docker](https://docs.docker.com/get-docker/) if not done so.

2. Clone the [pico-sdk](https://github.com/raspberrypi/pico-sdk) if not done so.

3. Clone the [project template](https://github.com/scott-cjx/RP2040-C-Docker-Template) repository.

4. Amend paths in `build.sh` file accordingly.

## Compiling Code
** Ensure Docker is running

Compile project with:
``` shell
sh build.sh
```
