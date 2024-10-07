
# Projet-responsive-app

Ce projet est une application web destinée à une agence immobilière, permettant aux employés de l'agence de gérer leurs ventes, leurs annonces, et d'accéder à des informations essentielles pour leur activité quotidienne. L'application inclut plusieurs pages interactives et des fonctionnalités adaptées aux besoins de l'agence.


## Installation

1. Clonez ce repository :
   ```bash
   git clone https://github.com/YannisYenoussi/Projet-responsive-app
   ```

2. Accédez au dossier cloné :
   ```bash
   cd projet-immobilier
   ```

3. Installez les dépendances :
   ```bash
   npm install
   ```

## Démarrage

1. Démarrez le serveur :
   ```bash
   npm start
   ```

2. Accédez à l'application via votre navigateur à l'adresse suivante :
   http://localhost:3006/home.html

## Pages

1. **Page Actualités** :
   - Affiche les actualités de l'agence, avec des questions interactives liées aux thèmes immobiliers.

2. **Page Base Clients** :
   - Gère la base de données clients de l'agence, avec des informations sur chaque client et des options de filtrage.

3. **Page Base Annonces** :
   - Affiche toutes les annonces en cours et archivées de l'agence avec des options de recherche et de tri.

4. **Page Mes Ventes** : 
   - Affiche les ventes et dossiers en cours pour l'utilisateur connecté ainsi qu'un historique de ses ventes.
   - Permet la recherche de ventes spécifiques.

5. **Page Chat et Appels** :
   - Contient un formulaire de recherche pour trouver des contacts, ainsi qu'une liste des discussions liées à l'utilisateur.

6. **Page Centre de Contact** :
   - Présente des encarts avec les informations de contact des différents référents (commercial, administratif, directeur d'agence).

7. **Page Analytique** :
   - Affiche divers graphiques et métriques sur les performances des ventes et des dossiers de l'agence.


## Technologies utilisées

- **Front-end** : HTML, CSS, JavaScript
- **Framework CSS** : Bootstrap

## Structure du projet

```
projet-immobilier/
│
├── src/
│   ├── views/
│   │   ├── actualites.html
│   │   ├── base-clients.html
│   │   ├── base-annonces.html
│   │   ├── ventes.html
│   │   ├── chat-appels.html 
│   │   ├── centre-contact.html
│   │   ├── analytique.html

│   └── ...
│
├── public/
│   ├── css/
│   ├── js/
│   ├── images/
│   └── ...
│
├── server.js
├── package.json
└── README.md
```


