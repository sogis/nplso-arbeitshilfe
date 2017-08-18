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

Create HTML output:

```
make html
```