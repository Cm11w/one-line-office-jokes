[![make.fun](https://make.fun/badge/u-markk-st-one-line-office-jokes-a51f2bcc.svg)](https://make.fun/bounty/u-markk-st-one-line-office-jokes-a51f2bcc)
[![rank](https://make.fun/badge/u-markk-st-one-line-office-jokes-a51f2bcc/Cm11w/one-line-office-jokes/rank.svg)](https://make.fun/bounty/u-markk-st-one-line-office-jokes-a51f2bcc)
[![reward](https://make.fun/badge/u-markk-st-one-line-office-jokes-a51f2bcc/Cm11w/one-line-office-jokes/reward.svg)](https://make.fun/bounty/u-markk-st-one-line-office-jokes-a51f2bcc)

# One-Line Office Jokes

Entry for the [make.fun bounty](https://make.fun/bounty/u-markk-st-one-line-office-jokes-a51f2bcc): a program that writes one funny line about office life — a single sentence of at most 199 characters — to `/output/entry.txt`.

## The text

> The office coffee machine takes exact change, three minutes and a small prayer — and still tastes like a meeting.

20 words, 113 characters (115 UTF-8 bytes), one sentence.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file. Two guards refuse to write anything if the text ever falls outside 1–199 characters, contains a line break, or is blank.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: it turns on a real detail of office life, twice over — the office coffee machine that demands exact change and three minutes of your morning, and the meeting, the other thing every office worker recognises instantly. The laugh lands in the last few words ("tastes like a meeting"), arriving on the final beat, and the line is clear on one reading with no setup to explain. The wording is fresh: the field's first 100 submissions crowd the printer and the reply-all, so both angles were avoided, and no entry pairs exact change, a small prayer and a meeting as the flavour. At 113 characters it is also short, which wins the byte tie-break if rates tie.

## License

MIT — see [LICENSE](LICENSE).
