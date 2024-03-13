Projet Spring Boot avec Docker et déploiement Jenkins
Ce projet est une application basée sur Spring Boot, conteneurisée avec Docker et déployée à l'aide de Jenkins.

Installation
Assurez-vous d'avoir Docker et Java installés sur votre machine.
Clonez ce dépôt sur votre système local.
Naviguez vers le répertoire du projet.
Utilisation
Construisez l'image Docker en exécutant la commande suivante :

Copy code
docker build -t nom_de_votre_image .
Lancez le conteneur Docker à partir de l'image construite :

docker run -d -p 8080:8080 nom_de_votre_image
Accédez à l'application en ouvrant un navigateur Web et en accédant à l'URL : http://localhost:8080.

Déploiement avec Jenkins
Ce projet est configuré pour être déployé automatiquement à l'aide de Jenkins.

Assurez-vous que Jenkins est configuré sur votre serveur.
Configurez un pipeline Jenkins pour surveiller ce dépôt.
Jenkins détectera automatiquement les modifications du code source et déclenchera le processus de construction et de déploiement.






