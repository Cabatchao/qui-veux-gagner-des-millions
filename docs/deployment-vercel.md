# Déploiement Vercel (avec votre compte GitHub)

## Pré-requis

- Avoir un compte GitHub avec ce dépôt poussé sur votre profil/organisation.
- Avoir un compte Vercel connecté à GitHub.

## Option A (recommandée) : import via dashboard Vercel

1. Aller sur https://vercel.com/new
2. Cliquer sur **Import Git Repository**.
3. Sélectionner ce dépôt GitHub.
4. Laisser les paramètres par défaut (site statique).
5. Cliquer sur **Deploy**.

Le projet est prêt pour ce flux avec une configuration Vercel minimale (`cleanUrls`) et `index.html` à la racine.

## Option B : via CLI Vercel

```bash
npx vercel login
npx vercel --prod
```

## Vérification rapide après déploiement

- Ouvrir l'URL Vercel.
- Vérifier :
  - affichage de la question,
  - timer 10s,
  - fin de partie si mauvaise réponse,
  - fin de partie en quittant l'onglet (anti-triche démo).

## Limitation actuelle

Cette version est un prototype frontend pour test rapide. La logique anti-triche finale doit être validée côté serveur dans la prochaine étape backend.
