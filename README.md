# Réseau Social Complet en React

## Aperçu

Ce projet est une application web de médias sociaux inspirée de LinkedIn. L'application permet aux utilisateurs de créer des publications, d'aimer, de commenter et d'interagir avec d'autres utilisateurs, en se concentrant sur la fourniture d'une interface utilisateur moderne et interactive à des fins de réseautage social.


Dépôt Backend : [Backend du Réseau Social](https://github.com/benalgodev/Social-Network-Backend)

## Fonctionnalités

- Authentification des utilisateurs (inscription, connexion, déconnexion)
- Créer, modifier et supprimer des publications
- Aimer et commenter les publications
- Pages de profil utilisateur
- Notifications en temps réel pour les nouveaux likes et commentaires
- Conception responsive pour différentes tailles d'écran
- État persistant utilisant le stockage local

## Installation

Pour commencer avec le projet, suivez ces étapes :

1. **Cloner le dépôt** :

   ```sh
   git clone https://github.com/benalgodev/React-Social-Media-App.git
   ```

2. **Naviguer dans le répertoire du projet** :

   ```sh
   cd React-Social-Media-App
   ```

3. **Installer les dépendances** :

   ```sh
   npm install
   ```

4. **Démarrer le serveur de développement** :

   ```sh
   npm start
   ```

L'application devrait maintenant fonctionner sur [http://localhost:3000](http://localhost:3000).

## Scripts Disponibles

- **`npm start`** : Exécute l'application en mode développement.
- **`npm test`** : Lance le lanceur de tests.
- **`npm run build`** : Construit l'application pour la production.
- **`npm run lint`** : Lint le code pour trouver et corriger les problèmes.

## Technologies Utilisées

- **React** : Framework frontal pour construire l'interface utilisateur.
- **Redux** : Gestion d'état pour les composants React.
- **React Router** : Pour gérer les routes de l'application.
- **Modules CSS et SASS** : Pour styliser les composants de manière modulaire et réutilisable.
- **Axios** : Pour effectuer des requêtes HTTP.
- **Node.js** : Environnement d'exécution backend.
- **Express** : Framework backend pour créer des API RESTful.
- **Socket.io** : Communication bidirectionnelle en temps réel basée sur les événements.
- **MongoDB** : Base de données pour stocker les données utilisateur et les publications.
- **Service Workers** : Pour activer les fonctionnalités hors ligne.

## Structure des Dossiers

- **src/**
  - **assets/** : Contient les images, icônes et autres ressources statiques utilisées dans l'application.
  - **components/** : Composants réutilisables principaux, tels que :
    - **Navbar.js** : Composant de barre de navigation.
    - **Post.js** : Composant pour afficher les publications individuelles.
    - **Profile.js** : Composant de profil utilisateur.
  - **hooks/** : Hooks personnalisés pour partager une logique réutilisable entre les composants.
  - **pages/** : Composants de page représentant différentes routes dans l'application :
    - **Home.js** : Page d'accueil de l'application.
    - **Login.js** : Page de connexion.
    - **Profile.js** : Page de profil utilisateur.
  - **services/** : Fonctions pour interagir avec les API externes (opérations CRUD, authentification utilisateur).
  - **store/** : Contient les configurations et slices du store Redux, tels que :
    - **userSlice.js** : Gestion d'état pour l'authentification utilisateur.
    - **postSlice.js** : Gestion d'état pour les publications.
  - **utils/** : Fonctions utilitaires pour les tâches répétitives.
  - **App.js** : Composant racine de l'application.
  - **index.js** : Point d'entrée pour le rendu de l'application.

## Déploiement

Pour déployer l'application, vous pouvez utiliser des plateformes comme Vercel, Netlify ou GitHub Pages. D'abord, construisez l'application en utilisant :

```sh
npm run build
```

Suivez ensuite les étapes de déploiement spécifiques à votre plateforme choisie.

## Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. Forkez le dépôt.
2. Créez une nouvelle branche (`git checkout -b feature/VotreFonctionnalité`).
3. Commitez vos modifications (`git commit -m 'Ajouter une fonctionnalité'`).
4. Poussez vers la branche (`git push origin feature/VotreFonctionnalité`).
5. Ouvrez une Pull Request.

## Contact

Si vous avez des questions ou des suggestions, n'hésitez pas à contacter le mainteneur du projet :

- **Nom** : benalgodev
- **Email** : benedictionmulemba@gmail.com
- **GitHub** : [https://github.com/benalgodev](https://github.com/benalgodev)

