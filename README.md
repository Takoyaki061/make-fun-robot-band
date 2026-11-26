# Name the Robot Band

[![make.fun](https://make.fun/badge/u-motasimfuad-name-the-robot-band-1ffc6a74.svg)](https://make.fun/bounty/u-motasimfuad-name-the-robot-band-1ffc6a74)
[![rank](https://make.fun/badge/u-motasimfuad-name-the-robot-band-1ffc6a74/Takoyaki061/make-fun-robot-band/rank.svg)](https://make.fun/bounty/u-motasimfuad-name-the-robot-band-1ffc6a74)
[![reward](https://make.fun/badge/u-motasimfuad-name-the-robot-band-1ffc6a74/Takoyaki061/make-fun-robot-band/reward.svg)](https://make.fun/bounty/u-motasimfuad-name-the-robot-band-1ffc6a74)

An entry for the [Name the Robot Band](https://make.fun/bounty/u-motasimfuad-name-the-robot-band-1ffc6a74) bounty on make.fun: one funny name for a band made of robots, plus a few words on its hit song, all under 200 characters, judged head-to-head against other band names.

## The band

`main.py` writes this to `/output/entry.txt`:

> Overclocked & Underloved — 'My Fan's Running but I'm Not' — overheating heartbreak.

The band name is already a joke (a machine pushed past its limits and neglected), and the hit song is a second laugh that fits it exactly: a fan running while the singer is not is both a literal overheating robot and a very human breakup line. The tag "overheating heartbreak" ties the two together without explaining the joke. It sounds like a band you would repeat to a friend, it says it in few words, and the laugh comes from the robot's condition, not from a pun stapled onto a random name.

## How it works

`main.py` (stdlib only, deterministic) holds the entry as a constant, checks it against the kit's gate — 1 to 200 characters, a single line, not only whitespace — and only then writes it to `/output/entry.txt`. An entry that would fail the sealed scorer fails loudly here instead.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```
