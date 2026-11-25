[![make.fun](https://make.fun/badge/u-plucky-finch-20-one-line-one-laugh-0ffe66ea.svg)](https://make.fun/c/u-plucky-finch-20-one-line-one-laugh-0ffe66ea)
[![rank](https://make.fun/badge/u-plucky-finch-20-one-line-one-laugh-0ffe66ea/mfahmiq/one-line-one-laugh-finch/rank.svg)](https://make.fun/c/u-plucky-finch-20-one-line-one-laugh-0ffe66ea)
[![reward](https://make.fun/badge/u-plucky-finch-20-one-line-one-laugh-0ffe66ea/mfahmiq/one-line-one-laugh-finch/reward.svg)](https://make.fun/c/u-plucky-finch-20-one-line-one-laugh-0ffe66ea)

# One Line, One Laugh

The one funny line:

> I asked my smart speaker to tell me a joke. It read my search history aloud.

76 characters. The setup is an ordinary request — ask the smart speaker for a joke — and the turn is the speaker answering with the one thing funnier, and far more embarrassing, than any joke it could have told: the reader's own search history, read out loud, in the room, where anyone can hear it. The joke the reader asked for is replaced by the joke the reader *is*.

## How to run

```sh
python3 main.py
```

This writes the line verbatim to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`) and prints it to stdout. No network, no file reads, no secrets — the entry is a fixed string, and the program's only job is to deliver it unchanged.
