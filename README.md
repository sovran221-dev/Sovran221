# SOVRAN 221 — Site Web Officiel

## Instructions d'installation

### Structure des fichiers
```
/index.html         → Page d'accueil
/about.html         → À Propos
/services.html      → Services
/process.html       → Processus
/case-studies.html  → Études de cas / Résultats
/contact.html       → Contact
/css/style.css      → Feuille de style principale
/js/script.js       → JavaScript principal
/assets/            → Images, logo, ressources
```

### 🖼️ LOGO — ACTION REQUISE
1. Placez votre fichier logo à `/assets/logo.png`
2. Le logo apparaîtra automatiquement dans :
   - La barre de navigation (header)
   - Le footer de chaque page
   - Le favicon du navigateur (onglet)

Le site est configuré pour afficher `logo.png`. Si le fichier est absent,
le nom textuel "SOVRAN 221" sera affiché à la place (fallback automatique).

### Images
Les images utilisent Unsplash (libres de droits) via URL directe.
Aucun téléchargement nécessaire pour les images de fond.

### Hébergement
Le site est 100% statique — aucun backend nécessaire.
Compatible avec : Netlify, Vercel, GitHub Pages, hébergement mutualisé.

### Performance
- Fonts Google Fonts (Cormorant Garamond + Montserrat)
- Images lazy-loaded
- CSS et JS minifiaux en production recommandés
- Animations CSS natives (pas de librairies lourdes)

### SEO
- Balises meta title/description sur chaque page
- Structure HTML sémantique (header, nav, section, article, footer)
- Attributs alt sur toutes les images
- Liens internes entre toutes les pages

---
© 2025 SOVRAN 221 — Dakar, Sénégal
