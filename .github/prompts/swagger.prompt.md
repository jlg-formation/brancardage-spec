---
name: swagger
description: Génération d'une spécification OpenAPI/Swagger
---

Génère une spécification OpenAPI 3.0 (Swagger) complète pour ce projet.

## Contexte à analyser

Analyse les dossiers `/docs` et `/input` pour extraire :

- Documentation fonctionnelle et technique du projet
- Spécifications et user stories
- Maquettes ou wireframes (si disponibles)
- Code source existant (si applicable)

## Éléments à produire

La spécification doit inclure :

- **Info** : titre, description, version de l'API
- **Serveurs** : URLs des environnements (dev, staging, prod)
- **Paths** : tous les endpoints avec leurs méthodes HTTP
- **Schemas** : modèles de données (request/response bodies)
- **Security** : schémas d'authentification utilisés
- **Tags** : regroupement logique des endpoints

## Bonnes pratiques

- Utiliser des noms de ressources RESTful (pluriel, kebab-case)
- Documenter tous les codes de réponse possibles (200, 400, 401, 404, 500...)
- Inclure des exemples pour les requêtes et réponses
- Ajouter des descriptions claires pour chaque endpoint et paramètre

## Output

`/swagger/api.yml`
