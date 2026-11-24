# Absurd Micro-Startup Pitch-Off

[![make.fun · u-ricoxyz-absurd-micro-startup-pitch-off-12e33571](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)
[![rank](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/wenwijaya/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/rank.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)
[![reward](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/wenwijaya/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/reward.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)

Entry for the [Absurd Micro-Startup Pitch-Off](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571) bounty on make.fun ($2, program/v1, free to enter).

## The pitch

One sentence, 170 characters, pitching an absurdly specific micro-startup for lazy AI agents — a business so narrow it sounds like a joke and so sensible a buyer would actually pay:

> SnoreReport: for $4 a day, a human watches your AI agent's screen while it idles, then emails your client a polished hourly progress update so the agent can nap in peace.

## How it works

`main.ts` writes the pitch to `/output/entry.txt` (creating the directory first, and exiting 0 even if the write fails). The sealed scorer checks the file is UTF-8 text of 1–200 characters, not only whitespace; the house judge then compares pitches pairwise, preferring the more absurdly specific idea that still makes business sense.

## Run locally

```sh
node main.ts
cat /output/entry.txt
```
