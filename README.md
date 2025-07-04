## An arm64 docker image for the [BeatDock Music Bot](https://github.com/lazaroagomez/BeatDock) for Discord, built by drifty

The official images do not exist, and I needed one for my Pi, so I cloned the repo and built the image myself. Useful for anyone with an arm64 processor who wants to run BeatDock. 

<!-- Also available on Docker Hub - [```driftywinds/cwa:latest```](https://hub.docker.com/repository/docker/driftywinds/cwa/general) -->

How to use: - 

1. Clone the original [repo](https://github.com/lazaroagomez/BeatDock).
2. Replace the "image" part of the ```docker-compose.yml``` to ```ghcr.io/driftywinds/beatdock-bot:latest```.
3. Follow the docker instructions of the repo (enable Discord intents etc.) and edit/make the ```.env``` file according to the requirements specified.
4. Within the BeatDock directory run ```docker compose up -d```.

<br>

You can check logs live with this command: - 
```
docker compose logs -f
```
