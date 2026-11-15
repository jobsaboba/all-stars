# All Stars Racing

Every **★★★★★ horse** in every race with **8+ runners** — that's the whole
rule. If the Grail rates it five stars and the field is big enough, it's on
the card.

- Never scores anything itself — the Holy Grail's published day files
  (`projects/holy-grail/data/`) are the sheet of record; this slices.
- **Its own ledger**, settled with the Grail's bet maths: **£10 bank · 1%
  of the bank on every pick · each-way at Ladbrokes (½ win · ½ place at
  1/5 odds)**. Void picks never stake; a race with a missing result stakes
  nothing until it's all in.
- The result — **WIN · PLACE · LOST** — lands next to each selection as
  results come in, with the stake → return and the bank after the race.

Published by `~/racing-scripts/all_stars.py --publish` — 05:15 each
morning (waits for the Grail's 05:00 sheet) and every 30 minutes,
13:00–22:00, via `results-refresh.sh` so results trickle in live.
