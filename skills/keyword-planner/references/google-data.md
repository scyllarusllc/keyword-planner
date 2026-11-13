# Google keyword data

Use this reference when importing Google Keyword Planner data or using Google Ads tools. This skill provides a research workflow, not an implemented Google Ads API client or an automatic account connection.

## Select an available path

1. Inspect available connected tools for keyword ideas or historical metrics and use their actual schema. Do not assume a Google Ads connector exists. When no sufficient connector exists, try an authorized signed-in browser using [google-browser.md](google-browser.md); no API developer token is required for this route.
2. If the user supplies a Keyword Planner export, inspect its encoding, delimiter, header rows, units, and metric meanings before processing it. Preserve original values and source provenance. Do not require credentials to process an export.
3. If no live connection, authorized browser, or export is available, continue with labeled qualitative research. Explain that measured Google metrics require an authorized connection or export; ask for this only when necessary to the requested result.

If asked to implement an API integration, verify current official prerequisites and API version first. Keep credentials out of chat and generated artifacts. Do not create campaigns, spend money, or change account settings as part of keyword research.

## Record the measurement context

Capture provider, retrieval/export date, geography, language, search network, date range, currency where relevant, and any filters. Mark unspecified settings unknown. Compare data only with compatible settings; keep different periods or locales separate.

Average monthly searches can include close variants. Returned ideas can canonicalize multiple variants, so do not sum overlapping variant metrics as independent demand. Preserve ranges rather than replacing them with midpoints. Historical metrics and forecasts answer different questions; label forecasts and retain budget, bids, dates, and other supplied assumptions.

Google Ads competition describes advertiser competition, not organic ranking difficulty. Top-of-page bid ranges are advertising bid metrics, not guaranteed costs or organic content value. Retain the original column meaning; do not silently rename every bid value “CPC.”

## Official references

Checked 2026-11-14; reopen the relevant page before relying on current API behavior or access requirements.

- Planning overview: https://developers.google.com/google-ads/api/docs/keyword-planning/overview
- Keyword ideas and targeting: https://developers.google.com/google-ads/api/docs/keyword-planning/generate-keyword-ideas
- Historical metrics: https://developers.google.com/google-ads/api/docs/keyword-planning/generate-historical-metrics
- Forecasts: https://developers.google.com/google-ads/api/docs/keyword-planning/generate-forecast-metrics
- UI metric definitions: https://support.google.com/google-ads/answer/3022575
