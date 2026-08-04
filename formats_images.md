---
layout: default
title: Formats d'image
permalink: /formats_images/
published: true
date: 2026
---

# Formats d'image : quel fichier pour quel usage ?

## 1. Deux grandes familles

**Image matricielle (bitmap)** : composée de pixels. Sa qualité dépend de sa définition (nombre de pixels). Agrandie au-delà de sa taille réelle, elle se pixellise.
→ Photos, textures, peinture numérique. Logiciels : Photoshop, Krita, Affinity Photo.

**Image vectorielle** : décrite par des formules mathématiques (points, courbes, aplats). Redimensionnable à l'infini sans perte de qualité.
→ Logos, icônes, illustrations, typographie. Logiciels : Illustrator, Figma, Inkscape, Affinity Designer.

## 2. Les formats à connaître

| Format | Famille | Compression | Transparence | Usage principal |
|---|---|---|---|---|
| JPEG (.jpg) | Matriciel | Avec perte | Non | Photos pour le web et l'échange |
| PNG | Matriciel | Sans perte | Oui | Captures d'écran, interfaces, images avec texte |
| WebP | Matriciel | Au choix | Oui | Format web standard actuel (léger, polyvalent) |
| AVIF | Matriciel | Avec perte | Oui | Format web de pointe, très léger |
| GIF | Matriciel | Sans perte (256 couleurs) | Oui | Historique ; remplacé par WebP/AVIF animés |
| TIFF | Matriciel | Sans perte | Oui | Impression, archivage haute qualité |
| PSD | Matriciel | — | Oui | Fichier de travail Photoshop (calques) |
| RAW (.CR3, .NEF, .DNG) | Matriciel | Sans perte | — | « Négatif numérique » des appareils photo |
| SVG | Vectoriel | — (fichier texte) | Oui | Logos et icônes pour le web, animable en CSS |
| PDF | Mixte | Au choix | Oui | Échange universel, envoi en imprimerie (PDF/X) |
| AI | Vectoriel | — | Oui | Fichier de travail Illustrator |

## 3. Quel format pour quel usage ? (mémo)

- Photo pour un site web → **WebP** (ou AVIF)
- Photo à envoyer par mail → **JPEG** (qualité 80 %)
- Logo ou icône pour le web → **SVG**
- Capture d'écran, maquette d'interface → **PNG**
- Image avec fond transparent → **PNG** ou **WebP**
- Document à imprimer → **PDF** (CMJN, 300 dpi)
- Photo destinée à l'impression → **TIFF** ou JPEG qualité maximale
- Fichier de travail → **PSD / AI / format natif** (à conserver toujours !)

## 4. Notions clés

**Compression avec perte / sans perte** : avec perte = fichier léger mais dégradation irréversible (JPEG). Sans perte = qualité intacte mais fichier plus lourd (PNG, TIFF).

**Définition et résolution** : la définition = nombre de pixels (ex. 1920 × 1080). La résolution (dpi) ne compte que pour l'impression : 300 dpi en standard. Pour un écran, seuls les pixels comptent.

**Modes colorimétriques** : **RVB** pour tout ce qui s'affiche à l'écran (profil sRGB pour le web), **CMJN** pour tout ce qui s'imprime. À vérifier avant d'envoyer un fichier en imprimerie.

**Fichier source ≠ fichier d'export** : on conserve toujours le fichier de travail avec ses calques (PSD, AI, Figma) et on exporte une copie dans le format adapté à la diffusion.

## 5. Bonnes pratiques

1. Nommer proprement ses fichiers : minuscules, sans espaces ni accents (ex. `affiche-expo-v2.webp`).
2. Ne jamais réenregistrer plusieurs fois un JPEG (dégradation cumulative).
3. Exporter à la dimension réelle d'usage, pas en pleine résolution.
4. Viser moins de 200–300 Ko pour une image web courante (éco-conception).
5. Vérifier le mode colorimétrique (RVB/CMJN) selon la destination.
6. Toujours garder ses fichiers sources (RAW, PSD, AI).
