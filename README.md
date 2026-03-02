# Kanap - Plateforme E-commerce (Vanilla JS)

> **Projet de formation : Maîtrise du JavaScript Front-end**
> *Objectif : Transformer une maquette statique en un site dynamique fonctionnel connecté à une API.*

## Ma Mission
Au sein d'une équipe agile, j'ai été chargée d'unifier le travail du CTO et du développeur Front-end en rendant le site "interactif". J'ai implémenté toute la logique métier, de l'affichage des produits jusqu'à la confirmation de commande.

## Fonctionnalités implémentées
- **Catalogue Dynamique** : Récupération et affichage automatique des produits via l'API Fetch.
- **Gestion de Panier (Le défi majeur)** : 
    - Stockage persistant via `localStorage`.
    - Gestion des doublons (regroupement par ID et couleur).
    - Mise à jour en temps réel des quantités et du prix total.
- **Validation de Formulaire** : Utilisation de **Regex** complexes pour valider les données client (email, nom, adresse) avant l'envoi.
- **Confirmation de Commande** : Gestion du tunnel d'achat et récupération de l'ID de commande envoyé par le backend.

## Stack Technique
- **Langage** : JavaScript ES6+ (Vanilla JS).
- **Architecture** : Code découpé en fonctions réutilisables et nommées (Clean Code).
- **Communication** : API REST (Promesses / Fetch).
- **Stockage** : LocalStorage pour la persistance du panier.

## Qualité & Tests
- Rédaction d'un **plan de tests d'acceptation** pour couvrir l'intégralité des parcours utilisateur.
- Gestion robuste des erreurs (cas où l'API est injoignable ou données invalides).

## Installation
1. **Clonez** le dépôt.
2. **Backend** : Allez dans le dossier `back` et lancez l'API (généralement `node server`). L'API tourne sur le port 3000.
3. **Frontend** : Ouvrez `index.html` dans votre navigateur (ou via Live Server).
