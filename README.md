# Révisions SAMA : dossier patient & identitovigilance

Site de révision pour le titre professionnel **Secrétaire assistant médico-administratif** :

- **Fiches** des 22 notions (mots définis en vert, terminologie en rouge)
- **Cartes mentales** style croquis, avec détail au survol et mode « Compléter » par glisser-déposer + auto-correction
- **Quiz** mélangé (67 questions) avec bilan des notions acquises / à retravailler
- **Checklist** latérale (progression enregistrée dans le navigateur)

Un seul fichier `index.html`, sans compilation ni dépendance.

## Mettre en ligne (GitHub + Netlify)

1. Créer un dépôt sur GitHub (par ex. `revisions-sama`) et y déposer les fichiers de ce dossier
   (`index.html`, `netlify.toml`, `README.md`, `.gitignore`).
   Sans ligne de commande : sur la page du dépôt, **Add file → Upload files**, glisser les fichiers, **Commit changes**.
2. Sur [app.netlify.com](https://app.netlify.com) : **Add new site → Import an existing project → GitHub**, choisir le dépôt.
3. Laisser *Build command* vide et *Publish directory* sur `.` (c'est déjà réglé par `netlify.toml`), puis **Deploy**.
4. Chaque modification poussée sur GitHub met le site à jour automatiquement.

## Tester en local

Ouvrir `index.html` dans un navigateur suffit.
