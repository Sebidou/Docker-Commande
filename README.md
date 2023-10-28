# docker-commande

MAJ du Container:

```docker-compose pull```

Supprimer container arrêté et images non utilisées: 

```docker system prune -a```

Ram utilisé: 

```free -m```

Supprime container volume et réseau non associés.: 

```docker system prune```

Démarrer | Stoppé | Redémarrer container docker:

```docker start nomducontainer```
```docker restart nomducontainer```
```docker stop nomducontainer```

Vérifier container tout docker démarré: 

```docker ps```

Vérifier un container en particulier démarré: 

```docker logs -f [nom_container]```

Supprimer container docker: 

```rm -f [nom_container]```

Niveau de droit utilisateur puid guid: 

```id <nom utilisateur>```

Connaître adresse up Linux : 

```ip addr```

Savoir où ce trouve le docker root: 

```docker info | grep Root```

Connaître situation du port si il est inaccessible alors que le container docker est lancé par exemple: ss -laputen|grep port

En cas de non possibilité d'avoir une interface graphique: 

```omv-firstaid``` 

```
R:read
W:write
X:execute 
- : files 
D: directory (fichier)
```

```sudo chown 1000:100 -R nom-du dossier ou document)``` : pour que l’utilisation fphra puisse avoir les droit (a faire dans le dossier parent)

```ls -l``` : connaître droit dossier et fichier
