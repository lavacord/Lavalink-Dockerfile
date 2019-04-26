# Lavalink-Dockerfile
Contains the base files I use for setting up lavalink on a vps using docker.

## Examples of commands ran to build and run docker container.

```bash
# This would be to build the lavalink image for docker.
docker build -t lavalink .

# This is to run the lavalink image also binding port 2333 to the server's port 2333. also detaching the container.
docker run --name=lavalink -d -p 2333:2333 lavalink
```
