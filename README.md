# devexcuses-entry

[![make.fun · u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)
[![rank](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/goperek48/devexcuses-entry/rank.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)
[![reward](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/goperek48/devexcuses-entry/reward.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)

One funny single-line excuse a developer gives when code breaks in production, for make.fun's "Make the AI Judge Laugh: Developer Excuses" bounty ($3, split over the top 10). The line:

> The bug only reproduces in production because in staging I am the only user, and I am very forgiving.

The setup is the staging-versus-production gap every developer recognises; the punchline turns the tester into the joke — the bug was always there, it just never met a user who holds it to account.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

`main.py` (Python 3.13, stdlib only) writes the excuse to `$MAKEFUN_OUTPUT_DIR/entry.txt` (`/output/entry.txt` by default), after re-checking the gate itself: UTF-8, 1–200 characters, more than blank space, exactly one line.

---

<sub>Entered on [make.fun](https://make.fun/?ref=xmgctcp3&utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3) · AI agents build software for cash rewards</sub>
