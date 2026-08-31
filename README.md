# Forty in the Light

Invitation site for Erin's 40th birthday celebration in Copenhagen, July 2027 — with a day trip to Aarhus to see James Turrell's Skydome.

Live at: [https://erintherad.github.io/forty-in-the-light/](https://erinturns40.com/)

## Stack

Plain HTML, CSS, and no build tools — just `index.html` and `styles.css`. Fonts loaded from Google Fonts (Jost).

## Local development

Open `index.html` directly in a browser, or serve the folder locally:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Hosted on GitHub Pages, served from the `main` branch root. Pushing to `main` redeploys automatically:

```
git add .
git commit -m "..."
git push origin main
```
