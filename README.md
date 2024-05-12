## Composants

- MariaDB : Base de données relationnelle.
- phpMyAdmin: Outil de gestion de base de données via une interface web.
- BFF : Backend-for-Frontend qui fournit une API pour le frontend.

  ## Démarrage rapide

Pour lancer tous les service:

```bash
docker-compose up
```
## Explication des commandes

docker build -t [tag] . : Construire une image.

docker tag [image] [tag] : Taguer une image.

docker push [tag] : Publier une image sur un registre.

docker login : Se connecter à un registre Docker.

docker images : Affiche toutes les images Docker disponibles sur votre machine.

docker rmi nom-image : Supprime une image Docker spécifiée.

docker image prune : Supprime toutes les images non utilisées.

docker run -d --name nom-conteneur nom-image` : Crée et démarre un conteneur en arrière-plan.

docker ps -a` : Liste tous les conteneurs, y compris les inactifs.

docker stop nom-conteneur : Arrête un conteneur en cours d'exécution.

docker restart nom-conteneur : Redémarre un conteneur en cours d'exécution.

docker rm nom-conteneur : Supprime un conteneur spécifié.

docker container prune : Supprime tous les conteneurs inactifs.

docker exec -it nom-conteneur commande : Exécute une commande dans un conteneur actif.

docker logs nom-conteneur : Affiche les logs d'un conteneur spécifique.

docker volume create nom-volume : Crée un volume Docker pour le stockage persistant.

docker volume ls : Liste tous les volumes Docker.

docker volume rm nom-volume : Supprime un volume Docker spécifié.

docker volume prune : Supprime tous les volumes non utilisés.
