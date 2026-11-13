# Google Keyword Planner: browser workflow

Use this path when the user wants real Google Keyword Planner research and an authorized, signed-in browser is available. It needs no developer token. It is a guided workflow for the host agent's browser tools, not a standalone browser driver or Google Ads API integration.

## Access and targeting

1. Open https://ads.google.com/aw/keywordplanner/home in the authorized browser and inspect the current page. Prefer an existing relevant tab. If login or account selection needs the user, hand over that step and continue independent preparation. Do not treat absent API credentials as proof the browser path is unavailable.
2. Choose **Discover new keywords** for suggestions and historical metrics. Use **Get search volume and forecasts** when an explicit list needs volume review; distinguish historical results from forecasts.
3. Enter a focused set of seed terms. Inspect the current UI limits instead of assuming an unlimited list.
4. Inspect location: a default such as United States may be wrong. Search for the exact target geography, include it, remove unrelated defaults, and verify the saved location. Reach in the location picker is not population or keyword volume.
5. Choose language explicitly and verify it again after editing seeds. Run different language conditions separately; input text language does not automatically change the language selector.
6. Record network, actual start/end months behind “Last 12 months,” active filters, retrieval date, and currency if bid data is used. Dates shown in the account timezone may differ from the user's local date.

## Run and verify

Submit the query, wait for loading to finish, and verify both the targeting controls and result rows. Editing keyword chips alone does not prove the query ran. If a UI click fails, inspect the page and use the available semantic browser action where appropriate rather than repeatedly clicking a stale element.

Record the returned canonical keyword alongside the submitted seed when they differ. Chinese terms may be displayed with inserted spaces. Inspect pagination: low-volume seeds may appear after the initial rows rather than being absent.

Check relevance before ranking. For example, a rental seed may produce car rental suggestions when the business needs housing. Refine with apartments, houses, or long-term intent and rerun. A store-name query may express navigation rather than interest in promotions. Exclude irrelevant ideas from recommendations while retaining an explanation of the decision.

Preserve ranges such as 0–10 and 10–100; never replace them with invented exact counts. A 0–10 range does not mean zero demand. A dash is unavailable data. Do not sum close variants as distinct audiences, infer organic difficulty from advertiser competition, or treat +∞ growth as a reliable forecast.

## Finish and protect research context

Save a compact table of selected rows, measurement context, exclusions, and limitations. Prefer a CSV download if the UI provides one; identify a manually transcribed subset as such. Retain evidence screenshots locally when useful, removing account identifiers before any public use.

Keyword research does not require creating campaigns, fixing billing, spending money, or saving keywords into existing campaigns. If Google restricts granularity or requires account action, report the limitation and continue with available ranges or qualitative evidence.

Return the actual findings and their implications. Keep account-derived metrics, screenshots, account IDs, and personalized URLs out of a public repository unless the user explicitly authorizes publication of those details. A public project may document the workflow and a hypothetical example without exposing a user's account.

For metric interpretation and API/export alternatives, see [google-data.md](google-data.md).
