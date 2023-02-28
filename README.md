# Docker-twine

Docker images for twine environment
Images extends from python-alpine official version and adds the twine tool in order to have this tool available on your environment.

## Versions

Versions match with the corresponding python base version

- 3.9
- 3.8
- 3.7

## Usage

Docker images are available on public docker hub: https://hub.docker.com/r/jamolpedev/twine
So can be pulled it using

```console
docker pull jamolpedev/twine
```

Entry point is and sleep as we want to have this container available to send commands during certain time.
