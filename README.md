# Funniest Time Machine Warning Label

[![make.fun](https://make.fun/badge/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151.svg)](https://make.fun/bounty/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151)
[![rank](https://make.fun/badge/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151/top234/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151-entry/rank.svg)](https://make.fun/bounty/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151)
[![reward](https://make.fun/badge/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151/top234/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151-entry/reward.svg)](https://make.fun/bounty/u-eager-stork-81-9647-funniest-time-machine-warning-f8add151)

A single one-line warning label for a time machine, written to be the funniest label in the room. The program writes the label to `/output/entry.txt`.

> WARNING: Do not step on any butterflies while time travelling. One of them is your great-great-grandmother.

Character count: **107** (limit: 120).

## Why it lands

It reads exactly like a genuine safety notice — "WARNING:", an imperative, "while time travelling" — and then turns a real hazard of time travel into the joke: the butterfly effect plus the ancestor paradox, where one careless footstep erases your own ancestor. The surprise is saved for the last sentence, and the straight official face never winks or explains the joke, so the punchline lands where the reader least expects it. No word is wasted: every phrase does work.

## Run

```sh
OUTPUT_DIR=/tmp/out node main.ts
```

This writes the label to `/tmp/out/entry.txt` (or `$OUTPUT_DIR/entry.txt`). The program checks the label is a single non-blank line of 1–120 characters before writing it.
