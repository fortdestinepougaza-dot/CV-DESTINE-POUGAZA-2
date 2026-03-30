# Portfilio

Portfolio personnel de **Destiné POUGAZA** — technicien réseau télécom & développeur.

## Contenu

- Page unique (`index.html`) : présentation, compétences, expériences, formations, contact.
- **CI/CD** : déploiement automatique sur **GitHub Pages** à chaque push sur `main` (workflow dans `.github/workflows/pages.yml`).

## Publier le dépôt sur GitHub

1. Créer sur GitHub un dépôt vide nommé **`Portfilio`** (sans README si tu pousses depuis le PC).
2. Dans le dossier du projet, ouvrir un terminal et exécuter :

```bash
git init
git add README.md
git commit -m "premier commit"
git branch -M main
git remote add origin git@github.com:leocca/Portfilio.git
git push -u origin main
```

Ensuite, ajouter le reste du site et pousser :

```bash
git add .
git commit -m "Ajout du portfolio (HTML, assets)"
git push
```

*(Si `origin` existe déjà : `git remote set-url origin git@github.com:leocca/Portfilio.git`.)*

HTTPS si besoin : `git remote add origin https://github.com/leocca/Portfilio.git`

## Déploiement (GitHub Pages)

1. **Settings** du dépôt → **Pages** → **Build and deployment** → **Source** : **GitHub Actions**.
2. Après push sur `main`, le workflow déploie le site.

URL du site : `https://leocca.github.io/Portfilio/`

## Fichiers à ajouter localement

À la racine du projet (à côté de `index.html`) :

- `top.png` — photo du portfolio  
- `cv.pdf` — CV en PDF (lien « Télécharger le CV »)

## Développement local

Ouvrir `index.html` dans un navigateur ou servir le dossier avec un serveur HTTP local.

---

© Destiné POUGAZA
