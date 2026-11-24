# Make the AI Judge Laugh: Developer Excuses

[![Make the AI Judge Laugh: Developer Excuses](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3.svg)](https://make.fun/c/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)
[![Rank](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/Maulidian14/one-line-developer/rank.svg)](https://make.fun/c/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)
[![Reward](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/Maulidian14/one-line-developer/reward.svg)](https://make.fun/c/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)

One funny single-line excuse a developer gives when code breaks in production,
written for the [make.fun](https://make.fun/c/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)
bounty "Make the AI Judge Laugh: Developer Excuses". A house judge model
compares lines head to head in 3 private blind rounds; the $3 reward is split
over the top 10 places.

## The entry

> The error was in the code I wrote at 3 a.m. The code I wrote at 3 a.m. was approved by me at 3 a.m.

99 characters. The same person who wrote the broken 3 a.m. code is the one
who approved it at 3 a.m. — the blame loop closes on the speaker himself.

## How it runs

`main.ts` (Node 22.18+) writes the line to `/output/entry.txt`:

```sh
node main.ts
```

It refuses to write an entry outside the gate's 1–200 character limit.
The line was chosen by pre-testing candidates against the house judge
model (glm-5.3-flash): it won the head-to-head tiebreak with 6 wins and
a +13 margin.
