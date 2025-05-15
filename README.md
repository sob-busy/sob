# Sob Galerie

**Sob Galerie** est un site web portfolio personnel permettant d'exposer tes créations artistiques, de partager des projets (liens d'applications) et de proposer tes services.

## Fonctions principales

- **Accueil** : Présentation générale.
- **Galerie** : Affichage de tes créations (images, vidéos à venir).
- **Projets** : Liste de tes applications ou projets avec liens.
- **Services** : Liste des services que tu proposes.
- **Contact** : Formulaire de contact fonctionnel avec [Formspree](https://formspree.io).

## Structure du site

- `index.html` : Le fichier principal du site.
- Design responsive basé sur **Tailwind CSS** (CDN).

## Configuration du formulaire

Le formulaire utilise **Formspree** :
```html
<form action="https://formspree.io/f/sob-l'antic" method="POST">
```
Tu peux gérer les messages reçus depuis ton compte Formspree.

## Publication gratuite

Voici trois options pour publier ton site :

### 1. Netlify (recommandé)
- Crée un compte sur [Netlify](https://www.netlify.com)
- Clique sur “Add new site” > “Deploy manually”
- Glisse le fichier `index.html` ou le dossier extrait dans l'interface
- Ton site sera en ligne avec une URL gratuite

### 2. Vercel
- Crée un compte sur [Vercel](https://vercel.com)
- Suis les mêmes étapes qu’avec Netlify

### 3. GitHub Pages
- Crée un dépôt GitHub
- Pousse le fichier `index.html`
- Active GitHub Pages depuis les paramètres

## Crédits

Développé par [TonNom]. Inspiré par une volonté de montrer et partager tes talents au monde.

---
© 2025 Sob Galerie. Tous droits réservés.

