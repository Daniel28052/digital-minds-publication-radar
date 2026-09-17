# Digital Minds Publication Radar

A lightweight web app for tracking researchers and reviewing their latest scholarly publications.

## What it does

- Adds researchers by name and optional affiliation.
- Matches each researcher to an OpenAlex author record.
- Retrieves publications from the past five years.
- Filters results by title, author, journal, and year.
- Saves selected papers to a local review list.
- Stores optional Google Scholar profile links for later verification.

## Data source

Automated discovery uses the public OpenAlex API. Direct Google Scholar scraping is intentionally avoided because it is fragile, frequently blocked, and may conflict with Google's automated-access rules.

## Run locally

Open `index.html` in a browser. Data is stored in that browser's local storage.

## Current scope

This first version is designed for one person's browser. A later version can add shared team accounts, scheduled scans, email alerts, and a central database.
