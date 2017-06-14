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
* [editorconfig-cli](https://github.com/amyboyd/editorconfig-cli) (e.g. `go get github.com/amyboyd/editorconfig-cli`)
* [flcl](https://github.com/mcandre/flcl) (e.g. `go get github.com/mcandre/flcl/...`)
