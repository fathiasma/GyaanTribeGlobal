Gyaan Tribe Global — Static Site

This folder contains a simple static website scaffold with the following pages:

- `index.html` — Home
- `about.html` — About Us
- `team.html` — Team
- `projects.html` — Our Projects

How to run locally

- Open `index.html` in your browser (double-click the file), or run a simple static server.

Using PowerShell to serve locally (Node.js required):

```powershell
# install a simple static server if you have Node.js
npm install -g serve
# run from this folder
serve . -p 3000
# then open http://localhost:3000
```

Next steps

- Add your logo file into `assets/` and swap the placeholders.
- Replace placeholder images with real photos and update copy.
- If you want a React/Vite build or a CMS integration (Netlify/Contentful/Sanity), I can scaffold that next.