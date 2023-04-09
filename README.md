Projet Infra
============

Solution: Autodéploiement d'une API sur serveur
-----------------------------------------------

### Sommaire

-   Introduction
-   Exécution du service
-   Fonctionnement du service
-   Conclusion

### Introduction

Le projet consiste à créer une solution d'autodéploiement d'une API sur un serveur. L'objectif est de simplifier le processus de déploiement de l'API pour les développeurs et les étudiants comme nous.

### Exécution du service

Le script pour exécuter le service se nomme `script` et se trouve sur notre Github. Pour l'exécuter, il est nécessaire de cloner le dépôt Github et d'exécuter le script à partir de la ligne de commande. Voici les étapes à suivre :

1.  Cloner le dépôt Github en utilisant la commande suivante :

`git clone https://github.com/Chenishere/Projetinfrab2`

1.  Accéder au répertoire cloné en utilisant la commande suivante :

`cd Projetinfrab2`

1.  Exécuter le script en utilisant la commande suivante :

`sh script.sh`

### Fonctionnement du service

Le service fonctionne en utilisant Docker pour créer un conteneur pour l'API. Le script effectue les opérations suivantes :

1.  Le script installe Docker.
2.  Construit l'image Docker de l'API en utilisant le Dockerfile fourni.
3.  Lance un conteneur pour l'image de l'API.
4.  Configure le pare-feu pour autoriser les connexions entrantes sur le port de l'API. Configure un fail2ban

Le script affiche également les informations relatives au conteneur, telles que son ID et son adresse IP.

### Conclusion

Le projet d'autodéploiement d'une API sur serveur a été réalisé avec succès. Le script fourni simplifie considérablement le processus de déploiement pour les développeurs et peut être facilement intégré à un pipeline de déploiement continu.
