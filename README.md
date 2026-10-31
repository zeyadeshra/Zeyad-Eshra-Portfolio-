# Zeyad Eshra · Personal Portfolio

A static, single-page site with no build step. It works on Vercel or GitHub Pages as-is.

## Structure
```
index.html                     ← the whole site
favicon.png
assets/Zeyad-Eshra-Resume.pdf  ← the Resume buttons open this file
assets/logos/                  ← ze-logo.webp, project logos (.webp), ze-lockup.jpg (social preview)
```

## Updating content
Open `index.html` and edit the `SITE` block marked **SITE CONTENT**: headline numbers, clients and markets, each product's numbers (`stats`), case studies (`cs`), services, lifecycle, operating model, experience and education.

## Updating the resume
Replace `assets/Zeyad-Eshra-Resume.pdf` with a new file that has the same name.

## Deploying (GitHub → Vercel)
1. Push this folder to a GitHub repo.
2. In Vercel, go to Add New → Project, import the repo, set Framework to "Other", leave the build command empty, then click Deploy.
3. Every push to `main` redeploys the site automatically.
