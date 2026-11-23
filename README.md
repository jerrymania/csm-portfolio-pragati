# Pragati Patil — Construction Site Management Practice (CSM) portfolio

Static website: plain HTML, CSS and a small optional JavaScript file. Fonts are bundled, so there are no external dependencies and nothing to build.

## View locally
Open `index.html` in a browser. (For the closest match to hosting, run `python3 -m http.server` in this folder and open http://localhost:8000.)

## Host it
- **Vercel:** import the folder (framework preset "Other", no build command, output directory `.`), or run `vercel` then `vercel --prod` inside the folder.
- **Netlify:** drag the folder onto app.netlify.com/drop.
- **GitHub Pages:** push the folder to a repository and enable Pages on the root of the main branch.

## Structure
```
index.html                 home: hero, identity, six PS cards, team photos
problem-statements/ps1–6   one page per problem statement
assets/css/main.css        design system
assets/js/main.js          mobile menu, scroll reveal, photo lightbox (optional)
assets/images/             cover portrait and team-discussion photographs
assets/fonts/              Instrument Serif, IBM Plex Sans, IBM Plex Mono (OFL)
assets/icons/favicon.svg
```

## Editing
Pages are generated from Python sources kept outside this folder; small text edits can be made directly in the HTML files.
