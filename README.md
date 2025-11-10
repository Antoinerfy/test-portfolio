# Portfolio GitHub Pages — Starter

Ce dépôt contient un portfolio minimal prêt pour GitHub Pages.

## Déploiement rapide

1. **Créer le dépôt sur GitHub :**
   - Nom recommandé : `votre-login.github.io` (pages utilisateur) **ou** tout autre nom (pages de projet).

2. **Envoyer les fichiers :**
   - Uploadez `index.html`, `style.css`, `assets/` et `README.md` à la racine.
   - Optionnel : ajoutez votre `CV.pdf` à la racine.

3. **Activer GitHub Pages :**
   - `Settings` → **Pages**.
   - **Source** : *Deploy from a branch*.
   - **Branch** : `main` (/**root**) ou `/docs` si vous placez les fichiers dans un dossier `docs/`.
   - Enregistrez. L’URL apparaît en haut de la section Pages.

> Astuce : si le dépôt s’appelle `votre-login.github.io`, la page est servie automatiquement depuis `main/` à la racine.

## Personnalisation

- Modifiez les textes dans `index.html` (nom, contact, projets).
- Remplacez les liens `#` par vos URLs (GitHub, Packet Tracer, rapports, etc.).
- Mettez votre `CV.pdf` à la racine et mettez à jour le lien du bouton.
- Ajoutez vos images dans `assets/` et référencez-les dans le HTML.

## Déploiement via git (ligne de commande)

```bash
git init
git add .
git commit -m "Init portfolio"
git branch -M main
git remote add origin https://github.com/votre-login/mon-portfolio.git
git push -u origin main
```

Puis activez **Pages** comme décrit ci-dessus.
