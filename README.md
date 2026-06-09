# Coldest Manus Feed

Public JSON feed for the Manus budget agent.

**Endpoint:** [`mer_for_manus.json`](https://raw.githubusercontent.com/davidstarkk/coldest-manus-feed/master/mer_for_manus.json)

**Refresh cadence:** Daily ~9:50 AM EDT, automated via the daily cashflow cron in the Coldest CFO Dashboard project.

**Schema:** see `schema_version` field inside the JSON. Includes pooled 7-day MER, target, breakeven, day-over-day and week-over-week deltas, and budget recommendation (action + magnitude).
