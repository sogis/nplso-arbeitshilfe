# nplso-arbeitshilfe

Sphinx documentation repository for "Arbeitshilfe ...[richtiger Titel]"

## System Requirements

* Docker
* git

## Usage

Clone this repository:

```
git clone https://github.com/sogis/nplso-arbeitshilfe.git $HOME/Projekte/nplso-arbeitshilfe
```

Start the Docker Container:

```
docker run -it -v $HOME/Projekte/nplso-arbeitshilfe:/documents/ sogis/docker-sphinx
``` 

This will take some time for the first time since it will download the whole docker image. You will be logged in into the running docker container. The terminal changes to something like `root@6f2114c76845:/documents#`.  

Create HTML output:

```
make html
```

To make a clean html output (that deletes everything in the output folder before build the html files):

```
make clean html
```

