# rupaktiwari.github.io

Personal website of Rupak Tiwari, live at **https://rupaktiwari.github.io**.

Plain HTML + CSS with no build step. GitHub Pages serves the `main` branch.

## Edit and publish

```bash
git clone https://github.com/rupaktiwari/rupaktiwari.github.io.git
cd rupaktiwari.github.io
# edit index.html / style.css
git add -A
git commit -m "Update site"
git push
```

The site updates about a minute after the push.

## Files

- `index.html`: all content (About, Experience, Publications, Projects, Skills, Education)
- `style.css`: styling (light and dark mode, mobile layout)
- `assets/profile.jpg`: profile photo
- `assets/Rupak_Tiwari_CV.pdf`: CV (replace this file to update it)
- `.nojekyll`: tells GitHub Pages to serve files as-is

To preview locally, run `python3 -m http.server` and open http://localhost:8000.
