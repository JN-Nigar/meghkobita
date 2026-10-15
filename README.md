# MeghKobita (মেঘকবিতা)

Every weather has a story. Every mood has a soundtrack.

A single-page static site: `index.html` contains the whole app (catalogue, engine and interface).
No build step and no environment variables. Live weather comes from Open-Meteo, which needs no API key.

## Deploy to Vercel

Option A, no install: go to https://vercel.com/new, choose "Import" from a GitHub repo containing these files,
keep Framework Preset = "Other", and click Deploy.

Option B, command line:

    npm i -g vercel
    cd meghkobita
    vercel --prod

You get a URL like https://meghkobita.vercel.app (or a variant if that name is taken).
