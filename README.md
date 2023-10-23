# Docker Roll 🚤

Performs a zero-downtime rollout of `service` using `docker compose up -d --scale SERVICE=2`

[![asciicast](https://asciinema.org/a/nO3JUNQdM9E660Lg27Q1OAe35.svg)](https://asciinema.org/a/nO3JUNQdM9E660Lg27Q1OAe35)

## Installation
```
mkdir -p ~/.docker/cli-plugins && \
    curl -Lso ~/.docker/cli-plugins/docker-roll https://github.com/synchrone/docker-roll/raw/master/docker-roll && \
    chmod +x ~/.docker/cli-plugins/docker-roll
```


