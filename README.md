# Atelier Nota – Perfume Creator

A single-page website where customers build their own perfume from floral, citrus, woody, spicy and musky notes.

## Features
- Pick notes and doses (1 to 3) from 26 notes across 5 scent families
- Live bottle visual, top / heart / base breakdown and scent-profile radar chart
- Resemblance matching against 8 well-known perfumes (cosine similarity on family balance)
- Mood presets, "Surprise me" and a "complete my blend" suggestion
- Customer reviews with star ratings (saved in the browser)
- Dark mode and mobile layout

## Run locally
Open `index.html` in a browser. No build step.

## Deploy with GitHub Pages
Repo Settings > Pages > Deploy from branch > `main` / root.

## Notes
The AI composer ("describe a scent") and shared reviews use the claude.ai artifact runtime, so outside claude.ai they switch off automatically and reviews stay local to each browser. To enable them on your own site, add a small backend that calls an AI API and a database for reviews.
