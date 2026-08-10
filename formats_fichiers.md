---
layout: default
title: Formats de fichiers
permalink: /formats_fichiers/
published: true
date: 2026
---

# Convention de nommage des fichiers

Pour vos projets : on n'invente pas sa convention : on adopte celle de l'écosystème dans lequel on travaille, et on s'y tient sur tout le projet.

Cette convention vise à garantir une organisation claire, lisible et compatible des fichiers numériques utilisés dans le cadre de vos projets (images, documents, maquettes, etc.).

Nous utiliserons la convention de nommage en **kebab-case** (mots séparés par des tiret comme s'ils étaient embrochés), sans majuscule, sans accents.

## Règles de base

- Utiliser uniquement des **minuscules**.
- Séparer les mots par un **tiret** (`-`) : `exemple-image-maquette.jpg`
- Ne jamais utiliser d'espaces, de majuscules ou de caractères accentués.
- Ne pas inclure de caractères spéciaux (`?`, `%`, `#`, `&`, etc.).
- Ajouter un suffixe clair pour la version : `-v1`, `-v2`, etc.
- **Jamais de `-final`** : pas de `-final`, `-final2`, `-vraiment-final`, `-final-ok`… Une nouvelle version = on incrémente le numéro.
- Viser des noms **courts et descriptifs** : environ 40 caractères maximum.

## Structure conseillée

```
[projet]-[description]-[version].[extension]
```

## Exemples

- `site-recette-tomates-v1.jpg`
- `affiche-stage-print-v1.pdf`
- `portfolio-accueil-v3.psd`

Respecter cette convention facilite le travail collaboratif, la relecture de vos projets, et évite les erreurs techniques liées à des noms de fichiers mal formatés.
