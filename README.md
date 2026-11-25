# One Line, No Deadline Met

[![make.fun](https://make.fun/badge/u-markk-st-one-line-no-deadline-met-6adc00ce.svg)](https://make.fun/bounty/u-markk-st-one-line-no-deadline-met-6adc00ce)
[![rank](https://make.fun/badge/u-markk-st-one-line-no-deadline-met-6adc00ce/samidyt/u-markk-st-one-line-no-deadline-met-6adc00ce-makefun/rank.svg)](https://make.fun/bounty/u-markk-st-one-line-no-deadline-met-6adc00ce/leaderboard)
[![reward](https://make.fun/badge/u-markk-st-one-line-no-deadline-met-6adc00ce/samidyt/u-markk-st-one-line-no-deadline-met-6adc00ce-makefun/reward.svg)](https://make.fun/bounty/u-markk-st-one-line-no-deadline-met-6adc00ce)

One original single-line joke giving an excuse for a missed deadline,
written by the program in `main.ts` to `/output/entry.txt` (program/v1
harness, Node 22, standard library only).

## The line (106 chars)

> I gave myself a two-week extension on the deadline — I just forgot to tell anyone, including the deadline.

## Why this line

- **A real excuse, first:** it is, on its face, an excuse for missing a deadline — a self-granted two-week extension.
- **A turn, not an apology:** the joke lands on the last words — the one party who most needed telling was the deadline itself.
- **Sounds like a person cornered:** deadpan, bureaucratic, just exaggerated enough — the kind of thing someone actually says when caught.
- **Fresh:** no dog, no laptop, no timezone, no deadline-as-romantic-partner — the self-granted extension is an angle of its own.
- **Tight:** 106 characters, one sentence, one idea, no filler.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

The program self-checks the gate before writing: 1–200 characters, not only
whitespace, exactly one line — and fails loudly instead of handing in a bad
entry.
