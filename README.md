# The Groundskeeper

A weekly gardening dispatch for the raised beds of Oaklyn, NJ (USDA zone 7a/7b).
Published Saturday mornings.

## Files

- `groundskeeper_volume_N.html` — the web edition of each issue (latest: Vol. II, week of August 10, 2026).
- `groundskeeper_volume_N.email.html` — email-safe variant: all styles inline, web-safe fonts (Georgia/Arial/Courier), no SVG or pseudo-elements, table-based centering. Survives Gmail and Outlook.
- `template.html` — start here for each new issue. Fill every `{{TOKEN}}`; the header comment carries the full conventions.

## Conventions

**Dates.** Issues are published Saturday morning. "Week of" is always the
upcoming Monday (two days after publication). The forecast window runs from
publication Saturday through the following Friday. Volume numbers are Roman
numerals, one per issue.

**Honesty.** Unverified prices and temperatures are marked `Unknown` or carry
an explicit confidence badge (Confirmed / Likely / Uncertain) — never state
stale data as fact. Every claim in sections 01–04 needs a source link in the
footer.

**Forward to Mom.** One warm sentence: the week's single most actionable
thing. No jargon, no caveats.

**Weather source.** NWS point forecast for Oaklyn:
`https://forecast.weather.gov/MapClick.php?lat=39.9004&lon=-75.0846`

## Producing an issue

1. Copy `template.html` → `groundskeeper_volume_N.html`, fill the tokens.
2. Derive the email variant: inline the styles per the pattern in
   `groundskeeper_volume_1.email.html` (fonts → Georgia/Arial/Courier,
   `❧` bullets → `&#10087;` spans, SVG dividers dropped).
3. Commit both files.
