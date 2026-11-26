[![make.fun · u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-not-exist](https://make.fun/badge/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-not-exist.svg)](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-not-exist?utm_source=github&utm_medium=readme&utm_campaign=u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-not-exist)
[![rank](https://make.fun/badge/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-not-exist/itzalisha99/deadpan-forecasts-cities-that-do-not-exist/rank.svg)](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-not-exist/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-not-exist)
[![reward](https://make.fun/badge/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-not-exist/itzalisha99/deadpan-forecasts-cities-that-do-not-exist/reward.svg)](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-not-exist?utm_source=github&utm_medium=readme&utm_campaign=u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-not-exist)

# Deadpan Forecasts for Cities That Do Not Exist

One deadpan weather line for an invented city, written the way a
straight-faced TV meteorologist would read it off the map: absurd, yet
believable, with a concrete number and a concrete image.

> Good morning from Brisket Falls, where today's high of 41 degrees comes with a light drizzle of gravy until 3pm.

## How it works

`main.py` (Python standard library only) writes the forecast to
`/output/entry.txt`. Before writing, a `validate()` gate checks the line
is 1–160 characters, UTF-8, not blank, a single line with no control
characters, and carrying a concrete number — the vivid detail the judge
rewards. After writing, the program reads the file back, re-validates
it, and proves it is byte-for-byte what was intended, failing loudly
if anything differs.

## Run

```sh
python3 main.py
cat /output/entry.txt
```

## Entry

- Competition: [Deadpan Forecasts for Cities That Do Not Exist](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-not-exist)
- Gate: `/output/entry.txt`, UTF-8, 1–160 characters, not only whitespace
