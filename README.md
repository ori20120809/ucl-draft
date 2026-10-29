# UCL Draft

A text-only fantasy football draft game prototype built around Champions League clubs.

## Run
Open `index.html` in any browser. No build step, no backend. Profile and squad are stored in `localStorage`.

## Status of this commit
This first commit contains the **foundation**: demo player database (`PLAYERS`), data metadata (`DATA_META`), game rules (budget, squad limits, formations, game modes), local persistence, navigation, Welcome, Sign Up / Guest, Dashboard and the Draft Room (filters, search, select/remove validation, auto-fill hooks).

Still to be added in follow-up commits: Squad Builder (formation + lineup + captain), Match simulation, Match Preview/Results, Leaderboard, Profile and Settings screens.

## Data
The database in `index.html` is a **clearly labeled demo database**. Players and clubs are real, but squad membership may be outdated and must be verified against a live source. Ratings, prices and attributes are invented **game values, not official statistics**. Replace the `RAW`/`PLAYERS` array with a live feed later.

## Disclaimer
Unofficial fan-made prototype. Not affiliated with UEFA or any club. No betting, no prizes, no payments. No player photos or club badges.
