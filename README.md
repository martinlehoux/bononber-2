## Installation

* `yarn`
* Configurer `config.json`
* `mkdir ~/mongo-data`
* `docker run -d -p 27017:27017 -v ~/mongo-data:/data/db mongo`
* `yarn start`
* Utiliser de préférence PM2

## Activer la webapp
* Servir le dossier `static/` pour l'url `/static/`
* Build la webapp :
    * `cd webapp`
    * `yarn build`
