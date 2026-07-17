# OMBRA — Lunettes de soleil

Site vitrine + e-commerce (checkout Shopify, essayage virtuel avec suivi du visage).

## Déploiement sur GitHub Pages

1. Dépose **tout le contenu de ce dossier** à la racine du repo (`index.html`, `support.js`, `ombra-data.js`, `img/`).
   Sur github.com : **Add file → Upload files**, glisse les fichiers + le dossier `img`, puis **Commit changes**.
2. Dans le repo : **Settings → Pages → Source : Deploy from a branch → Branch : main / (root) → Save**.
3. Après ~1 minute, le site est en ligne sur :
   `https://lrcars06-blip.github.io/ombra/`

Notes :
- HTTPS obligatoire pour la caméra de l'essayage — GitHub Pages est en HTTPS, rien à faire.
- Aucun build, aucune dépendance à installer : fichiers statiques uniquement.
