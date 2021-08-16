# YSFReflector Docker Image

This repository only contains Docker build considerations to produce an image from `master` of [`https://github.com/g4klx/YSFClients/YSFReflector`](https://github.com/g4klx/YSFClients). It will be available as `neilbartley/ysfreflector` at:

* [Docker Hub](https://hub.docker.com/r/neilbartley/ysfreflector)
* [GitHub](https://hub.docker.com/r/neilbartley/ysfreflector)

# Running

## Requirements

* [Docker](https://docs.docker.com/install/)
* Firewall setup to accept `42000/udp`

## Usage

`docker run -e REFLECTOR_NAME="YOUR_NAME_HERE" -e REFLECTOR_DESCRIPTION="YOUR_DESCRIPTION_HERE" -p 42000:42000/udp --name=ysfreflector neilbartley/ysfreflector:latest`

# Contact

73, G7UFO
g7ufo@neil.bar
