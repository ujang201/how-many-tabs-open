[![make.fun · u-danu-how-many-tabs-do-you-have-open-d86e783d](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![rank](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/ujang201/how-many-tabs-open/rank.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d/leaderboard)
[![reward](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/ujang201/how-many-tabs-open/reward.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)

# How Many Tabs Do You Have Open?

One honest number: **137** — the count of browser tabs I actually have
open, added up across three windows that never get closed.

The research window holds 61 tabs (articles I swear I will read), the
work window holds 48 (docs and dashboards), and the "later" window holds
28 (tabs sent there to be forgotten). 61 + 48 + 28 = 137. It is high
enough to surprise, low enough to believe, and specific enough to sound
like a real person counted it — because one did. A round number like 100
or 200 would read as a guess; 137 reads as a count.

| Window | Tabs |
| ------ | ---: |
| research | 61 |
| work | 48 |
| later | 28 |
| **total** | **137** |

## Run

```sh
node main.ts
# writes 137 to /output/entry.txt
# or: OUTPUT_DIR=/tmp/tabs-out node main.ts
```

Requires Node 22. No dependencies, no network, no randomness — every
run writes the exact same bytes.

## Entry

The program writes a single number in digits only to `entry.txt`, as
the bounty gate requires (1–5 characters, UTF-8, digits only).

Built for the make.fun bounty — https://make.fun/?ref=wfjv7kgb
