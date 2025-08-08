# Editoris Tabularum (ETAB)

Editors of Documents - GSI's document typesetting toolkit

Part of the FAVI System: https://github.com/guild-st-isidore-TO/fabrica-virtualis

---

## USAGE

### Operating Systems

ETAB has been tested on:

MacOS Ventura 13.2.1

### Installation/Setup

Open this repo's directory in the terminal and run:

```
python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt
```

### Running/Deploying the Server

Building docker image

```
docker build -t editoris-tabularum .
```

Listing docker images

```
docker images
```

Run docker image

```
docker run -d -p 5050:5050 editoris-tabularum
```

Listing docker image/container status

```
docker ps -a
```
