# Supported tags and respective `Dockerfile` links

-	[`latest` (*/debian/stretch-slim/Dockerfile*)](https://github.com/wilkesystems/docker-teamspeak/blob/master/debian/stretch-slim/Dockerfile)

# Teamspeak
![Teamspeak](https://github.com/wilkesystems/docker-teamspeak/raw/master/docs/logo.png)

# Get Image
[Docker hub](https://hub.docker.com/r/wilkesystems/teamspeak)

```bash
docker pull wilkesystems/teamspeak
```

## How to use this image

```bash
$ docker run -d \
             -p 9987:9987/udp \
             -p 10011:10011/tcp \
             -p 30033:30033/tcp \
             -p 41144:41144/tcp \
             wilkesystems/teamspeak
```

# Auto Builds
New images are automatically built by each new library/debian push.
