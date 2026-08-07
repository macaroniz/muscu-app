# muscu-app

PWA de tracking musculation (saisie en salle hors ligne, rappel de la derniere seance,
progression, volume, correlations). **Aucune donnee personnelle ici** : ce repo ne
contient que le code ; les donnees vivent dans le repo prive `muscu-data`, accede
via l'API GitHub avec un fine-grained PAT saisi dans l'app.

- `index.html` — app complete (mono-fichier, zero framework, zero build)
- `sw.js` — service worker (cache de l'app shell, fonctionne hors ligne)
- `manifest.webmanifest` + icones — installation sur l'ecran d'accueil iOS
