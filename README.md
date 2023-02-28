# Docker-twine

Docker images for twine environment
Images extends from python-alpine official version and adds the twine tool in order to have this tool available on your environment.

## Versions

Versions match with the corresponding python base version

- 3.9
- 3.8
- 3.7

**3.1 and amd1** are specific tags used for a process where due incompatibilities by different architectures (m1 processor) sleep command was forced to be included as entrypoint I do not recommend using this ones as you can not configure the sleep (set to 99)

## Usage

Docker images are available on public docker hub: https://hub.docker.com/r/jamolpedev/twine
So can be pulled it using

```console
docker pull jamolpedev/twine
```
