# Kaoutar Belail — Portfolio

A bilingual (EN/FR), responsive, Light Elegant portfolio built with React, Vite and Tailwind CSS.

## Run locally

```bash
npm install
npm run dev
```

Open the local URL displayed by Vite.

## Personalize

1. Add your professional photo as `public/profile.jpg`.
2. Add your CV as `public/cv.pdf` (the download link will work once it exists).
3. Edit `src/content.js`: add your professional email and LinkedIn URL in `profile`, and adjust projects, descriptions and dates as needed.
4. To add project screenshots, replace the decorative project placeholders in `src/App.jsx`.
5. Change the accent color in `tailwind.config.js` if desired.

## Build

```bash
npm run build
npm run preview
```

## Deploy to GitHub Pages

For a repository named `BELAILKaoutar.github.io`, push this project's files to the repository's `main` branch and configure GitHub Pages with a GitHub Actions workflow for Vite (or use a static deployment service). The default Vite base `/` works for a user-site repository. For a project repository under a subpath, set `base: '/repository-name/'` in `vite.config.js` and adjust asset URLs accordingly.

## Notes

The contact email and LinkedIn are intentionally blank until confirmed. The AI project is a general placeholder rather than a fabricated project case study. This portfolio is a first version intended for customization.

## Visuals
Add genuine project screenshots to `public/projects/` and official company logos to `public/companies/`. Filenames are documented in those folders. Technology icons use Devicon via jsDelivr (internet required). Company initials and project placeholders appear until assets are added.


## Galeries réelles et dépôts
Les 48 captures transmises sont intégrées dans `public/gallery/`. Chaque projet possède une galerie Web / Mobile, avec navigation et agrandissement. Les liens GitHub / GitLab sont renseignés dans `src/content.js`.

Pour le déploiement GitHub Pages sur un dépôt de type `BELAILKaoutar.github.io`, la racine `/` fonctionne. Pour un dépôt de projet sous `/nom-du-repo/`, configurez `base` dans `vite.config.js` et utilisez `import.meta.env.BASE_URL` pour les images.
