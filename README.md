# Projet Nuxt 3 avec préparation pour Nuxt 4

Ce projet est une base de départ pour les applications web utilisant Nuxt 3, avec une préparation pour une transition future vers Nuxt 4. Il intègre plusieurs outils et frameworks modernes pour assurer une expérience de développement optimale.

## Fonctionnalités principales

- **Nuxt 3** : Framework moderne basé sur Vue.js pour le rendu côté serveur (SSR) et le rendu statique (SSG).
- **Préparation pour Nuxt 4** : Structure et configurations compatibles avec une mise à jour future vers Nuxt 4.
- **ESLint** : Linter pour maintenir un code propre et cohérent.
- **Tailwind CSS** : Framework CSS utility-first pour une conception rapide et réactive.
- **Nuxt/UI** : Ensemble de composants prêts à l'emploi pour accélérer le développement d'UI.
- **Nuxt/Font** : Gestion simple des polices pour optimiser les performances et le design.
- **Nuxt/Icon** : Intégration facile d'icônes dans l'application.

## Installation

1. Clonez ce dépôt :

   ```bash
   git clone https://github.com/hte88/nuxt-base-project.git
   cd nuxt-base-project
   ```

2. Installez les dépendances :

   ```bash
   pnpm install
   ```

3. Lancez le projet en mode développement :

   ```bash
   pnpm dev
   ```

4. Accédez à l'application dans votre navigateur :

   ```
   http://localhost:3000
   ```

## Scripts disponibles

- `pnpm dev` : Démarre le serveur de développement.
- `pnpm lint` : Analyse le code avec ESLint.

## Structure du projet

```
app/
├── assets/         # Fichiers statiques comme les images
├── components/     # Composants Vue.js réutilisables
├── layouts/        # Modèles de mise en page
├── pages/          # Pages de l'application
├── plugins/        # Extensions et plugins Nuxt
├── utils/          # Fonctions utilitaires
├── middleware/     # Middleware pour la gestion des requêtes
├── composables/    # Fonctions réutilisables avec la Composition API
├── layouts/        # Modèles de mise en page
public/             # Fichiers statiques accessibles publiquement
server/             # Code côté serveur
nuxt.config.js      # Configuration principale de Nuxt
```
