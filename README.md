# Calcul Cycles Moteur FIA — v1.0

Application web progressive (PWA) d'aide au remplissage des FIA pour le calcul des cycles moteur.

## Installation

### GitHub Pages (recommandé)
1. Créer un nouveau dépôt GitHub (ex: `fia-cycles`)
2. Uploader tous les fichiers de ce dossier à la racine du dépôt
3. Aller dans **Settings → Pages → Branch: main → / (root)** → Save
4. L'app sera disponible à : `https://[votre-pseudo].github.io/fia-cycles/`

### Installation sur l'appareil

**iPhone / iPad (Safari)**
→ Ouvrir l'URL → icône Partager → "Sur l'écran d'accueil"

**Android (Chrome)**
→ Ouvrir l'URL → menu ⋮ → "Ajouter à l'écran d'accueil"

**Ordinateur (Chrome / Edge)**
→ Ouvrir l'URL → icône ⊕ dans la barre d'adresse → Installer

## Fonctionnement hors-ligne
Une fois installée, l'application fonctionne **sans connexion internet**.

## Fichiers
```
index.html      — Application principale
manifest.json   — Configuration PWA
sw.js           — Service Worker (cache hors-ligne)
icons/          — Icônes pour tous les appareils
```

## Version
**1.0** — Calcul NG1, NG2, TC avec tous les types de vol
