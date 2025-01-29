
# Homelab Project - EN COURS !

Ce projet a pour objectif de déployer un homelab avec plusieurs services basés sur des conteneurs Docker :  
- Serveur web  
- Serveur mail  
- Serveur proxy  
- Serveur VPN  
- Serveur de partage de fichiers  

## Prérequis
- Docker
- Docker Compose

## Configuration
Modifiez le fichier `.env` selon vos besoins pour personnaliser les paramètres d'exécution.

## Lancement du homelab
Exécutez la commande suivante pour lancer tous les services :

```bash
docker-compose up -d
```

## Services inclus
### Serveur Web
Accès via : [http://localhost:8080](http://localhost:8080)

### Serveur Mail
Un serveur mail de base avec Postfix et Dovecot.

### Serveur Proxy
Proxy inversé basé sur Nginx.

### Serveur VPN
OpenVPN configuré pour les accès sécurisés.

### Serveur de partage de fichiers
Basé sur Samba pour un partage de fichiers local.

## Arborescence du projet
```plaintext
HomeLab/
    ├── README.md
    ├── docker-compose.yml
    ├── .env
    └── services/
        ├── web-server/
        │   └── Dockerfile
        ├── mail-server/
        │   └── Dockerfile
        ├── proxy-server/
        │   └── Dockerfile
        ├── vpn-server/
        │   └── Dockerfile
        └── file-server/
            └── Dockerfile
```

## Contribution
N'hésitez pas à proposer des améliorations ou à signaler des bugs via des issues sur le dépôt GitHub.


##  Contact
 
-	Auteur : Fatih KILIC
-	GitHub : [https://github.com/Fatih-RT](https://github.com/Fatih-RT)
-	Portfolio : [portfolio.fatih-kilic.fr](portfolio.fatih-kilic.fr)

## Licence
Ce projet est sous licence MIT.
