> Documenter le déploiement. Créer un fichier `README.md`. 

---

# myExpressApp

- Version : **[1.0.0]**
- Auteur: **[Christopher Ares]**

## Description des fonctionnalités

myExpressApp est une application de connexion à un serveur.
Elle permet de définir des routes afin d'acceder à certaines pages du site web.

### Fonctionnalités principales

- Route vers accueil : /accueil

- Route vers a propos : /about

- Route vers hello : /hello/:name

- Route vers error404 : Si aucune route ne correspond à la requête

## Stack Technique

* **Frontend :*CSS 5* 
* **Backend :*nodejs 18* 
* **Frameworks :*express* 
* **Base de données :*Aucune* 

## Environnement d'exécution

Ce projet nécessite un environnement compatible avec les spécifications suivantes :
- Docker

## Installation & Démarrage

### Option 1 : Via Docker (Recommandé)

Tapez dans la console :
- docker build -t nomduconteneur .
- docker run -d -p 3000:80 nomduconteneur

### Option 2 : Installation manuelle (Alternative sans Docker)

Dans la console :
- npm init
- package name: indiquez le nom du fichier (ex: index.js)
- version: 1.0.0
- description: 
- npm install express

## Cas d'erreur
- Il se peut que votre Docker fasse déjà tourner un conteneur sur le même port, dans ce cas vous aurez une érreur.
