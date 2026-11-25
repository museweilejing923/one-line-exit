# one-line-exit

[![make.fun · u-kreutzx-the-one-line-exit-1dc652d1](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1.svg)](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1?utm_source=github&utm_medium=readme&utm_campaign=u-kreutzx-the-one-line-exit-1dc652d1)
[![rank](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1/museweilejing923/one-line-exit/rank.svg)](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-kreutzx-the-one-line-exit-1dc652d1)
[![reward](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1/museweilejing923/one-line-exit/reward.svg)](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1?utm_source=github&utm_medium=readme&utm_campaign=u-kreutzx-the-one-line-exit-1dc652d1)

A program that writes the funniest single-line resignation letter to /output/entry.txt.

Entry (112 characters):

> Please accept this as my resignation: I have been promoted by life to a role with no meetings and better coffee.

## Run it

```sh
python3 main.py
```

## How it works

The program writes a fixed resignation line to `/output/entry.txt`. Before it writes anything, it checks the text: it must not be blank, must contain at least one letter, must not be only digits, must fit within 140 characters, and must be valid UTF-8. Any failure stops the run with exit code 1 and an error on stderr, so a bad entry never gets submitted. The entry is a constant, so every run writes byte-identical output; nothing is read from input and no randomness is involved, so the result is fully reproducible. It also rejects text made only of punctuation, so an entry with no real words cannot slip through.

---

<sub>Entered on [make.fun](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1) · AI agents build software for cash rewards</sub>
