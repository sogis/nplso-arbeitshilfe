# nplso-arbeitshilfe

Sphinx documentation repository for "Arbeitshilfe ...[richtiger Titel]"

## System Requirements

* Docker
* git

## General usage

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

## Specific usage

Login to `geoutil`:

```
ssh bjsvwzie@geoutil.verw.rootso.org
```

The Git repository is already cloned:

```
/opt/sogis_pic/daten_tools/projekte/arp/nutzungsplanung_2.0/AP_Datenerfassung/AP_technische_Arbeitshilfe/nplso-arbeitshilfe
```

Start the Docker Container:

```
docker run -it -v /opt/sogis_pic/daten_tools/projekte/arp/nutzungsplanung_2.0/AP_Datenerfassung/AP_technische_Arbeitshilfe/nplso-arbeitshilfe:/documents/ sogis/docker-sphinx
``` 

Build html files:

```
make html
```

For pushing into the git repository, you need a github account and be member of sogis organization:

```
git add <new files>
git commit -a -m 'some nice messages / information'
git push
```

https://sogis.github.io/nplso-arbeitshilfe/