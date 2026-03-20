# Email Scraper — CRM Enrichment Tool

Upload an Excel file of business leads → auto-fills emails → download enriched file.

**Live tool:** https://charliemaynard2109-ux.github.io/email-scraper

## Setup

1. Push these files to a GitHub repo called `email-scraper`
2. Go to **Settings → Pages → Source: GitHub Actions**
3. Push to `main` — auto-deploys in ~1 minute

## API Keys needed

- **Anthropic key** (required) — [console.anthropic.com](https://console.anthropic.com)
- **Google Custom Search key + CX** (recommended, 100 free/day) — [developers.google.com/custom-search](https://developers.google.com/custom-search/v1/introduction)

Keys are saved in each user's own browser — nothing stored centrally.

## Excel format

Needs at minimum: Business Name, Address/Location, Postcode columns.
Column names can be anything — you map them in the UI.

The tool adds two columns to your download: `Email` and `Email Confidence`.
