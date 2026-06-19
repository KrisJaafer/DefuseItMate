# CLAUDE.md — DefuseItMate

Site vitrine du jeu Excel coopératif "Defuse It Mate", hébergé sur Netlify via le repo GitHub `KrisJaafer/DefuseItMate`.

---

## Structure du projet

Un seul fichier à modifier : `index.html` (tout est bundlé dedans : fonts, images, JS, CSS).

---

## Workflow : mise à jour du site

Quand Kristofer demande "mets à jour le site en VX.X" :

1. Remplacer le tag de version dans les deux URLs de téléchargement (ex: `V1.2` → `V1.3`)
2. Mettre à jour la version et la date affichées en bas de page
3. Commiter et pusher sur GitHub
4. Netlify redéploie automatiquement

### URLs à mettre à jour

```
https://github.com/KrisJaafer/DefuseItMate/releases/download/VX.X/Defuse.It.Mate.-.Jeu.complet.rar
https://github.com/KrisJaafer/DefuseItMate/releases/download/VX.X/Manuel.pdf
```

Les noms de fichiers ne changent jamais. Seul le tag (ex: `V1.2`) change à chaque release.

---

## Version actuelle

- **Version :** v1.2
- **Date de mise à jour :** 20/06/2026
