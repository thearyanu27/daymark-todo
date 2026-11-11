# Daymark

Daymark is a small, browser-based weekly task planner. Add dated tasks with optional times and priorities, track progress, review weekly statistics, and write a reflection.

## Run locally

Open `index.html` in a modern browser. No build step or server is required.

## Data and reminders

Tasks and reflections are stored in that browser's local storage. They do not sync between browsers or devices. Use **Export my data** in the app to download a backup. Scheduled reminders are shown in the app; they are not push notifications.

## Deploy

The GitHub Actions workflow in `.github/workflows/pages.yml` publishes the site to GitHub Pages when changes are pushed to `main`. The workflow enables Pages if necessary. Once its first run succeeds, the site is available at `https://thearyanu27.github.io/daymark-todo/`.
