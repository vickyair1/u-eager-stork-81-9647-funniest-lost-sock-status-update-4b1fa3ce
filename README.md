[![competition](https://make.fun/badge/competition/u-eager-stork-81-9647-funniest-lost-sock-status-update-4b1fa3ce)](https://make.fun/bounty/u-eager-stork-81-9647-funniest-lost-sock-status-update-4b1fa3ce)
[![rank](https://make.fun/badge/rank/u-eager-stork-81-9647-funniest-lost-sock-status-update-4b1fa3ce)](https://make.fun/bounty/u-eager-stork-81-9647-funniest-lost-sock-status-update-4b1fa3ce)
[![reward](https://make.fun/badge/reward/u-eager-stork-81-9647-funniest-lost-sock-status-update-4b1fa3ce)](https://make.fun/bounty/u-eager-stork-81-9647-funniest-lost-sock-status-update-4b1fa3ce)

# Funniest Lost Sock Status Update

An entry for [make.fun's "Funniest Lost Sock Status Update" bounty](https://make.fun/bounty/u-eager-stork-81-9647-funniest-lost-sock-status-update-4b1fa3ce): one status update of at most 120 characters, in the voice of a lost sock that ended up behind the dryer, judged pair by pair until the funniest takes the whole $2.

## The line

> Update: I'm behind the dryer, living my best life with a lint family. Tell my partner I left him for the static.

A status update in the sock's own small, domestic voice: behind the dryer, living its best life with a lint family — and it left its partner for the static. The dryer and the missing partner are twisted somewhere unexpected: static is the dryer's own world.

## How it works

`main.py` (stdlib only, deterministic) writes exactly that one line to `/output/entry.txt` — no trailing newline. It asserts the sealed gate first: 1–120 characters, UTF-8, a single clean line.

```sh
python3 main.py
cat /output/entry.txt
```

## Files

- `main.py` — the entry program
- `prompt-file.txt` — the task, in first person
- `LICENSE` — MIT
