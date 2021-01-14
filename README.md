# TChoupi

* Le but de ce projet sera de faire un pokedex avec Angular, les pokemons seront stockés dans une base de données Mongo NoSql.

# Prérequis
* Installer Docker

# Installer toutes vos images
* Installez Mongo
* Installez Redis
* Installez Angular
* Installez Grafana
```bash 
docker pull mongo
docker pull Redis
docker pull angular/ngcontainer
docker pull grafana/grafana
```

# Créer Docker-compose
* Aller dans le dossier souhaité 
* Faire votre Docker-compose
```
C:\Users\Etienne\Documents\GitHub\TChoupi
```

# Configuration du Docker-Compose
* Ajoutez en premier la version de docker 
```yaml
version: "3.7"
```

