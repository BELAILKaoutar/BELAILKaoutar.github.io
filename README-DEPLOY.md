# Publication GitHub Pages

1. Créer un dépôt **public** `BELAILKaoutar.github.io` sur le compte GitHub `BELAILKaoutar` (sans README initial).
2. Dans le dossier du projet : `npm install`, puis `npm run build`.
3. `git init` ; `git add .` ; `git commit -m "Initial portfolio"` ; `git branch -M main` ; `git remote add origin https://github.com/BELAILKaoutar/BELAILKaoutar.github.io.git` ; `git push -u origin main`.
4. Sur GitHub : Settings > Pages > Build and deployment > Source : **GitHub Actions**.
5. Onglet Actions : attendre que **Deploy portfolio to GitHub Pages** réussisse.
6. Ouvrir https://belailkaoutar.github.io/ (le chemin est insensible à la casse côté nom de domaine).

À chaque modification : `git add .` ; `git commit -m "Update portfolio"` ; `git push`.

**Note :** si le dépôt porte un autre nom (ex. `portfolio`), définir `base: '/portfolio/'` dans `vite.config.js`. Les chemins absolus `/gallery/...`, `/companies/...`, `/profile.jpg` et `/cv.pdf` devront aussi être adaptés au sous-chemin : ce projet est préparé pour le dépôt racine `BELAILKaoutar.github.io`.
