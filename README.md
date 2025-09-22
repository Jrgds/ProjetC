## Projet C

Le cahier des charges reçu pour la réalisation du Projet C :

Installation et configuration d’une application monolithique et de l’ensemble de son écosystème manière automatisée via pipeline CI/CD en veillant à intégrer des principes DevSecOps. Transformer une application monolithique en microservices et l’intégrer de manière automatisée via pipeline CI/CD en veillant à intégrer des principes DevSecOps. Mettre à profit toutes les compétences acquises lors de la formation dans le projet (Azure ou AWS, Ansible, Kubernetes, Apache ou Nginx, …) Définir l’architecture cible en limitant les points de faiblesse de l’infrastructure choisie tout en améliorant la sécurité de l’application dans son ensemble.


#### Notions complémentaires :
##### DevSec:

* sécuriser le code source
* réaliser les tests fonctionnels


##### SecOps :

*  sécuriser des configurations
*  sécuriser les accès
*  sécuriser des environnements
*  réaliser les tests d’infrastructure
*  réaliser les tests de sécurité
*  supervision (infra et applicative)


## Les outils choisis

* GitLab (free trial) pour la création d’un Groupe de projet (privé) et le registre des fichiers du projet et des conteneurs Docker du micro-service

* Hub Docker pour le registre du conteneur Docker de Owncloud server

* AWS (pour le déploiement de l’application monolithique et du micro-service on cloud)

* Terraform (pour déployer l’infrastructure avec l’installation de Docker, Ansible et Nginx)

* Ansible (pour déployer l’application monolithique et le micro-service)

* Vscode (création du code et pour faire le ‘push’ des fichiers / images Docker vers GitLab et Hub Docker)

* Powershell (connexion à chaque instance EC2)

* Reprise de l’application monolithique et le micro-service du [Projet B](https://github.com/Jrgds/ProjectB/tree/dev). (Owncloud server et le micro-service « gestion de mot de passe »)


## L'architecture mise en place

![This is an alt text.](https://github.com/Jrgds/ProjetC/blob/main/ProjetC.png "This is a sample image.")


## Vidéos du projet final présenté

* [Deployement_CI-CD_Infra _ ProjetC.mp4](https://drive.google.com/file/d/1prHYL4_c_fqnAZooHybRIOSKssAVNlh8/view?usp=sharing)
* [Deployement_CI-CD_App et Nginx _ProjetC.mp4](https://drive.google.com/file/d/12w_p91nN1LIefWEKsTCuOjN4XZ3Kweug/view?usp=sharing)
* [Deployement_CI-CD_Microservice _ ProjetC.mp4](https://drive.google.com/file/d/1UH95NRjZYZeKpopuPRi-ebtz3zKMeTX9/view?usp=sharing)
* [Déployement_manuel_ProjetC.mp4](https://drive.google.com/file/d/1AapQOkY-R5vWvvJbnL3CqMGJJz0VEzIE/view?usp=sharing)

