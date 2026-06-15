# Magic Chrono

Application web mobile transformée en PWA installable.

## Installation sur GitHub Pages

1. Crée un dépôt GitHub, par exemple `magic-chrono`.
2. Envoie tous les fichiers de ce dossier dans le dépôt.
3. Dans GitHub : **Settings → Pages**.
4. Source : **Deploy from a branch**.
5. Branch : `main` / dossier `/root`.
6. Ouvre l’URL GitHub Pages générée.

## Installer sur téléphone

### Android / Chrome
- Ouvre l’URL GitHub Pages.
- Menu ⋮ → **Ajouter à l’écran d’accueil** ou **Installer l’application**.

### iPhone / Safari
- Ouvre l’URL GitHub Pages dans Safari.
- Bouton partager → **Sur l’écran d’accueil**.

## Structure

- `index.html` : application Magic Chrono.
- `manifest.webmanifest` : configuration d’installation mobile.
- `sw.js` : cache offline basique.
- `icons/` : icônes générées depuis l’icône fournie.

## API plus tard

L’app contient déjà un système d’événements côté navigateur avec `window.MagicChronoLastEvent`. Plus tard, une API pourra être ajoutée avec `fetch()` dans la fonction `publish(event, extra)`.
