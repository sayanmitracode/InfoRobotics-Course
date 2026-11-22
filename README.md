# InfoRobotics-Course: ECE 598 IBR website

Source for the Spring 2027 website of ECE 598 IBR, Information Bottlenecks in Robotics, built with Material for MkDocs.

## Local preview

    python3 -m venv .venv && .venv/bin/pip install -r requirements.txt
    .venv/bin/mkdocs serve        # http://127.0.0.1:8000

## Editing

Pages live in `docs/`. The navigation is in `mkdocs.yml`. Lecture PDFs go in `docs/assets/pdfs/` and are linked from `docs/schedule.md`, for example `[Notes](assets/pdfs/L03_myhill_nerode.pdf)`. Announcements go at the top of the list in `docs/index.md`.

## Deployment

Pushing to `main` runs `.github/workflows/deploy.yml`, which builds the site and publishes it to GitHub Pages. In the repository settings, set Pages > Source to "GitHub Actions".
