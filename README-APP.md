# All Stars Racing

Every **★★★★★ horse** in every race with **8+ runners** — that's the whole
rule. If the Grail rates it five stars and the field is big enough, it's on
the card.

- Never scores anything itself — the Holy Grail's published day files
  (`projects/holy-grail/data/`) are the sheet of record; this slices.
- **Its own ledger — Jacobs Ladder staking**: £10 bank, **10p a unit,
  ladder starting 1-2-2** so the first bet is (1+2)×10p = **30p**. One
  ladder across the whole season, walked race by race: a **loss appends
  the bet to the ladder** (30p → 40p → 50p…), a **win scratches first and
  last** off it (reset when two or fewer remain), and **any new bank high
  resets straight back to 1-2-2**. Each-way at Ladbrokes (½ win · ½ place
  at 1/5 odds), settled with the Grail's bet maths. Non-runners are
  refunded with no ladder move; a race with a pick still to run shows its
  planned stake but stakes nothing.
- The result — **WIN · PLACE · LOST** — lands next to each selection as
  results come in, with the stake → return and the bank after the race.

Published by `~/racing-scripts/all_stars.py --publish` — 05:15 each
morning (waits for the Grail's 05:00 sheet) and every 30 minutes,
13:00–22:00, via `results-refresh.sh` so results trickle in live.
