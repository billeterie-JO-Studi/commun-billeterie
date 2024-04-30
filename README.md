# Billeterie JO

ce dépot contient l'ensemble des repositories de la billeterie pour faciliter le déploiement continue.

## Installation

### Avec un réseau Docker 

pour installer le projet

1. cloner le projet avec : `git clone --recurse-submodules git@github.com:billeterie-JO-Studi/commun-billeterie.git`
2. modifier les variable d'environemment dans le docker-compose.yml selon vos besoins. 
2. lancer le réseau docker docker compose `docker-compose up -d`

### Avec Kubernetes 

#### Prérequis 

- [Kubernetes](https://kubernetes.io/)

#### Installation 

utiliser le fichier de configuration kubenetes.yml pour lancer le cluster Kubernetes
`kubectl apply -f kubernetes.yml`




