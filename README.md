# docker-bash - a Docker container for bash

# DOCKER HUB

https://registry.hub.docker.com/u/mcandre/docker-bash/

# EXAMPLE

```
$ make run
docker run mcandre/docker-bash bash -c "echo $SHELL"
/bin/bash
```

# REQUIREMENTS

* [Docker](https://www.docker.com/)

## Optional

* [make](http://www.gnu.org/software/make/)
* [Node.js](https://nodejs.org/en/) (for dockerlint)
