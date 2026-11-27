# TailwindCssProjet — 

## Technologies

| Outil | Rôle |
| --- | --- |
| [Nuxt 4](https://nuxt.com) | Framework Vue (serveur de dev, build) |
| [Vue 3](https://vuejs.org) | Composants de la page |
| [Tailwind CSS](https://tailwindcss.com) (via `@nuxtjs/tailwindcss`) | Mise en forme et responsive |

## Prérequis

- [Node.js](https://nodejs.org) **version 20 ou plus** (vérifier avec `node -v`)
- npm (installé avec Node.js) **ou** [Bun](https://bun.sh)

## Installation et lancement

```bash
# 1. Récupérer le projet
git clone https://github.com/Pape42/TailwindCssProjet.git
cd TailwindCssProjet

# 2. Installer les dépendances
npm install        # ou : bun install

# 3. Lancer le serveur de développement
npm run dev        # ou : bun run dev
```

Ouvrir ensuite **<http://localhost:3000>** dans le navigateur.
Pour arrêter le serveur : `Ctrl + C` dans le terminal.

## Autres commandes

| Commande | Description |
| --- | --- |
| `npm run build` | Construit la version de production |
| `npm run preview` | Lance localement la version de production construite |
| `npm run generate` | Génère un site statique (dossier `.output/public`) |

## Structure du projet

```text
TailwindCssProjet/
├── app/
│   ├── app.vue                 # Page principale (assemble les composants)
│   ├── assets/css/tailwind.css # Import des styles Tailwind
│   └── components/
│       ├── header.vue          # Barre latérale + en-tête « My catalogs »
│       └── corps.vue           # Grille des cartes de catalogues
├── public/                     # Fichiers statiques (favicon, robots.txt)
├── nuxt.config.ts              # Configuration Nuxt (module Tailwind)
├── tailwind.config.js          # Configuration Tailwind
└── package.json                # Dépendances et scripts
```

## Couleurs principales

| Couleur | Code | Utilisation |
| --- | --- | --- |
| Violet | `#463ADD` | Boutons, début du dégradé du logo |
| Rose | `#FF00FB` | Survol des boutons, dégradé du logo |
| Bleu clair | `#EEF1FF` | Fond de la barre latérale |
| Gris clair | `#F9F9FB` | Fond des étiquettes de catégories |
