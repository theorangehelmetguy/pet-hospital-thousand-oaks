# The Pet Hospital of Thousand Oaks

Website for [thepethospitalto.com](https://thepethospitalto.com). Plain HTML, CSS and a little JavaScript. No build step.

## Pages
- `index.html` (home), `services.html`, `about.html`, `contact.html`, `404.html`
- Images live in `/images`

## Hosting
Deployed on Netlify from the `main` branch. Every push goes live in about a minute.
- Clean URLs (`/services`) are served automatically from `services.html`.
- Old Squarespace URLs redirect in `netlify.toml`.

## Forms
The booking form and newsletter signup use Netlify Forms. Submissions show in Netlify under **Forms**, and email notifications go to info@thepethospitalto.com (set in Site settings > Notifications).

## Editing
Edit the HTML file for the page, commit and push. Hours, phone and address also appear in the structured data block (`application/ld+json`) at the top of each page, so update both.
