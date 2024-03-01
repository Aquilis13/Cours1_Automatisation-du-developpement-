# Nom
`CHANOT Flora`

# Prérequis 
- Docker avec Docker compose d'installés
- Configurer le fichier .env en fonction de votre environnement qui se trouve [ICI](https://github.com/Aquilis13/Cours1_Automatisation-du-developpement-/blob/develop/docker/.env)

# Lancement 
Tous les services se lancent en même temps avec ces commandes :  
``` bash
# Ce placer dans le répertoire docker du projet
cd docker/

# Lancer les services
docker compose up
```

# immo-api-php
Par défaut, l'API est accessible à l'adresse suivante :  
http://0.0.0.0:8020/

# immo-client-vue
Par défaut, le projet VueJS est accessible à l'adresse suivante :  
http://0.0.0.0:3000/

# immo-admin-react
Par défaut, le projet React est accessible à l'adresse suivante :  
http://0.0.0.0:3020/