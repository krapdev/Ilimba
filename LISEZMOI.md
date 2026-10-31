# Ilimba v0.22.2 — version GitHub Pages (installable)

Cette version s'installe comme une appli : sur iPhone, lancée depuis l'icône de l'écran d'accueil, elle s'ouvre **sans aucune barre Safari** ; sur Android, en vrai plein écran. Elle marche aussi hors-ligne après la première visite.

## Mise en ligne (une seule fois)
1. Sur https://github.com/krapdev/Ilimba : **Add file → Upload files**, glisse **tout le contenu** de ce dossier (index.html, manifest.webmanifest, sw.js, .nojekyll, dossier icons/) à la racine du dépôt, puis **Commit**.
2. **Settings → Pages** → Source : *Deploy from a branch* → Branche : `main`, dossier `/ (root)` → **Save**.
3. Après 1 à 2 minutes, le jeu est en ligne sur **https://krapdev.github.io/Ilimba/**
   (Pages gratuit = dépôt **public** ; un dépôt privé demande un compte GitHub payant.)

## Installer sur iPhone
Ouvre l'adresse dans **Safari** → bouton **Partager** → **Sur l'écran d'accueil** → lance Ilimba depuis l'icône.

## Installer sur Android
Ouvre l'adresse dans **Chrome** → menu ⋮ → **Installer l'application** (ou « Ajouter à l'écran d'accueil »).

## Mettre à jour
Remplace `index.html` et `sw.js` par ceux de la nouvelle version (le nom du cache dans `sw.js` change à chaque version, ce qui force la mise à jour chez les joueurs).
Le bouton « Ouvrir la version appli » de la version itch.io pointe vers https://krapdev.github.io/Ilimba/ — si l'adresse change, dis-le-moi.
