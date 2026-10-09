# Le Volant VIP — Journal statique

Site statique du journal mensuel « Le Volant VIP » (Rivesud.limo).

## Contenu

- `index.html` — édition d'octobre 2026 (fichier unique, images intégrées en base64).

## Déploiement

Ce dépôt est conçu pour être connecté à DigitalOcean App Platform comme
**static site** :

1. Pousser ce dépôt sur GitHub.
2. Sur DigitalOcean App Platform : Create App → GitHub → choisir ce dépôt.
3. Type de composant : **Static Site** (sortie : `/`).
4. Aucune commande de build nécessaire (le HTML est prêt).

Le site est 100 % statique : aucun serveur, aucune dépendance.
