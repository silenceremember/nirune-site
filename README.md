# NIRUNE website

Static product, privacy, and terms website for NIRUNE.

The site is intentionally dependency-free and contains no analytics or tracking
scripts. The canonical deployment is `https://nirune.site/`; publish this
directory without a build step.

## Pages

- `/` — product homepage
- `/privacy/` — privacy and provider-session disclosure
- `/terms/` — terms of service

## Local preview

From this directory:

    python -m http.server 8088

Then open `http://127.0.0.1:8088/`.
