# Countdown to Saturday

Single-file countdown: `index.html`.

Live: https://teds-son-1000.github.io/countdown-saturday/

## What it does
- Counts down to next Saturday 00:00 local time
- Celebrates on arrival, then rolls to the following Saturday

## Fixes in this version
- Correct Saturday logic (next Saturday, not today unless midnight)
- Celebrate re-entrancy guard (fires once per arrival)
- Audio node cleanup (no leak on repeated fanfares)
