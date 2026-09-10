# Suivi ESIEA — Rayan

Tableau de suivi de progression pour le cycle ingénieur ESIEA (FISA).

## Structure

```
public/
  index.html   ← la page web
  data.json    ← les données (matières, sujets, statuts)
```

## Mettre à jour

Pour mettre à jour ta progression, modifie `public/data.json`.

Chaque sujet a :
- `name` : nom du sujet
- `status` : `compris`, `en_cours`, ou `pas_commence`
- `source` : `cours` (vu en classe), `tutorat` (avec Claude), ou `les_deux`
- `note` : commentaire optionnel

## Déployer sur Vercel

1. Push ce dossier sur un repo GitHub
2. Va sur [vercel.com](https://vercel.com) et connecte ton compte GitHub
3. Importe le repo → Vercel détecte automatiquement la config
4. C'est en ligne !

Chaque push sur `main` redéploie automatiquement.
