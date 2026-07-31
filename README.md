# NIRUNE website

Static product and OAuth verification website for NIRUNE.

The site is intentionally dependency-free and contains no analytics or tracking
scripts. GitHub Pages publishes the `main` branch. The intended custom domain is
`nirune.is-a.dev`.

## Pages

- `/` — product homepage
- `/privacy/` — privacy policy and Google user-data disclosure
- `/terms/` — terms of service

## Local preview

From this directory:

    python -m http.server 8088

Then open `http://127.0.0.1:8088/`.
