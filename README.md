# Moot Court and Writing Competitions Tracker

Moot court competitions and writing competitions for law students and young lawyers, with live deadlines, countdowns, a yearly calendar and the busiest months.

Live site: https://moot-writing-tracker.github.io

## Files

- `index.html`: the page (layout, styles and logic).
- `data.js`: every competition and its dates. Update this file when new information arrives.
- `logo.png`: site icon and profile image.

## Data format

Each entry in `ITEMS` has a type (`t: "m"` for moots, `t: "w"` for writing), a name, description, state, source tag and a list of dates. `EXP` holds months expected from past cycles, shown as "Expected" and never as confirmed.

Always check dates against the official page before you submit.

Maintained by Raymond Angu'zu.
