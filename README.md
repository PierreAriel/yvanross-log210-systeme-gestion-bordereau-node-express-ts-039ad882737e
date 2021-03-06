# Système de gestion des bordereau utilisé dans le cadre du cours de LOG210 et développé avec Node, Express et TypeScript

Ce système doit être utilisé pour obtenir l'information de base à la réalisation de votre laboratoire en LOG210. Il possède les qualités suivantes:

 - il est simple pour les débutants en LOG210
   - il n'y a pas de framework pour le front-end ni pour la persistance, mais ça n'empêche pas d'ajouter ces dimensions.
   - il est seulement [REST niveau 1](https://restfulapi.net/richardson-maturity-model/#level-one), mais ça n'empêche pas de modifier l'API pour qu'il soit [REST niveau 3](https://restfulapi.net/richardson-maturity-model/#level-three). 
 - il est orienté objet (avec TypeScript)
 - il contient des tests pour l'API (avec Mocha)
 - il fait une séparation entre les couches présentation et domaine, selon la méthodologie de conception du cours LOG210 (Larman)

## Voulez-vous utiliser ce serveur?

1. (Créer une fork et) Cloner
2. Installer les dépendences node - ```npm install```
3. Compiler - ```npm run build```
4. Lancer serveur de développement - ```npm start```
5. Lancer les tests (pas besoin de lancer le serveur d'abord) - ```npm test```

## Exécution des test
npm run test -- -g "nom ou partie du nom d'un test"
npm run test
npm run coverage

## Pour exécuter un test unitaire
**npm run test** -- -g 'responds with successful call for students with valid teacher token'

## définition de l'API

voir le fichier docs/index.html
