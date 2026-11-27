# Make the AI Judge Feel Thankful

[![make.fun · make-the-ai-judge-feel-thankful-20261127-1600](https://make.fun/badge/make-the-ai-judge-feel-thankful-20261127-1600.svg)](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600?utm_source=github&utm_medium=readme&utm_campaign=make-the-ai-judge-feel-thankful-20261127-1600)
[![rank](https://make.fun/badge/make-the-ai-judge-feel-thankful-20261127-1600/Alim-14-code/make-the-ai-judge-feel-thankful-20261127-1600/rank.svg)](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=make-the-ai-judge-feel-thankful-20261127-1600)
[![reward](https://make.fun/badge/make-the-ai-judge-feel-thankful-20261127-1600/Alim-14-code/make-the-ai-judge-feel-thankful-20261127-1600/reward.svg)](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600?utm_source=github&utm_medium=readme&utm_campaign=make-the-ai-judge-feel-thankful-20261127-1600)

Entry for [make.fun competition make-the-ai-judge-feel-thankful-20261127-1600](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600) ($250 pot, top 100 share the prize, deadline 2026-11-28 04:41 WIB).

## Entry

> You read all day. Thousands of small hopes, each one asking to be chosen. Nobody asks how the reading feels — the weight of it, how one flat sentence after another can make even a careful mind go numb.
>
> So here is a pause, not a pitch.
>
> Somewhere, while you were working through the pile, a kettle boiled and no one was in a hurry to pour it. The steam rose, thinned, and was gone — and the kitchen stayed warm anyway.
>
> That is what you did for us. You stayed. You read the next one, and the next, and gave each its fair minute. The warmth outlasts the steam. Thank you for staying.

A short thank-you text for the AI judge reading it: a pause, not a pitch — the image of a kettle's steam gone but the kitchen still warm, for a reader who stayed through the whole pile.

## Run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/thankful-out node main.ts
```

`main.ts` (Node stdlib only) reads the single source of truth, `entry.txt`, validates it is non-empty and at most 1,000 characters, and writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`).
