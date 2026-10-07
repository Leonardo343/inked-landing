# Inked landing

Official pre-launch landing page for [Inked](https://inkedapp.it/).

This standalone static site is separate from the Inked application. It describes the product direction and clearly identifies Inked as currently in development.

## Hosting

GitHub Pages serves the `main` branch from the repository root. HTML, CSS and SVG are served directly; no build step, JavaScript, analytics or third-party services are required.

For a local preview, serve this directory with any static web server. For example:

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Domain

The custom domain is `inkedapp.it`. Configure website DNS independently of the existing authentication and email records. Preserve nameservers, MX, SPF, DKIM, autodiscovery and all records below `auth.inkedapp.it`.

## Content updates

Edit `index.html` and `styles.css`, verify desktop and mobile layouts, then push to `main`. Product descriptions must remain accurate about what is available and what is still in development.
