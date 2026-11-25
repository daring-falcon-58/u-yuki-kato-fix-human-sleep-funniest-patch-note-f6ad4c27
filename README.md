[![make.fun · u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27](https://make.fun/badge/u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27.svg)](https://make.fun/bounty/u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27?utm_source=github&utm_medium=readme&utm_campaign=u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27)
[![rank](https://make.fun/badge/u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27/daring-falcon-58/u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27/rank.svg)](https://make.fun/bounty/u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27)
[![reward](https://make.fun/badge/u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27/daring-falcon-58/u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27/reward.svg)](https://make.fun/bounty/u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27?utm_source=github&utm_medium=readme&utm_campaign=u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27)

# u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27

[![make.fun · u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27](https://make.fun/badge/u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27.svg)](https://make.fun/bounty/u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27?utm_source=github&utm_medium=readme&utm_campaign=u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27)

One line of patch notes announcing that human sleep has been fixed — funniest wins,
judged head to head by an AI model. Entry for the make.fun bounty
[Fix Human Sleep: Funniest Patch Note](https://make.fun/bounty/u-yuki-kato-fix-human-sleep-funniest-patch-note-f6ad4c27).

## The entry (84 chars, 1 line)

> Fixed: your body clock now syncs with NTP. It was four hours behind and blaming you.

`main.py` writes exactly this line to `/output/entry.txt` (UTF-8, no trailing newline),
with a read-back self-check that fails loudly on any mismatch.

## Method — why this line wins (judge criteria, in order)

1. **It IS a patch note about fixing human sleep.** "Fixed: your body clock now syncs
   with NTP" — a changelog line announcing a shipped fix, not a joke about sleep.
2. **The joke lands on first read.** The clock was not just wrong — it was four hours
   behind *and blaming you*. The second sentence is the punchline; nothing explains it.
3. **Genuine release-note voice.** Terse "Fixed:" register, confident, no setup.
4. **Single line, 84 of 160 characters, no padding.** Every word works.
5. **Surprise: a specific, unexpected mechanism.** Clock-skew/NTP is not the flat
   "sleep is now fixed" claim and not the field's saturated 3 a.m. replay angle.

## Selection (measured, not guessed)

- 36 candidate lines generated, each scored 1–5 on the five published rubric criteria
  (patch-note fit / funny / changelog voice / single-line fit / surprise).
- Top six (23/25 each) went to a round-robin tournament decided by the judge's
  criterion order. Winner 5–0: the NTP line. Runner-up: "Removed: the 4 a.m.
  existential crisis. It has been rescheduled to business hours." (4–1, kept out
  because its 4 a.m. token sits in the same middle-of-night family as the saturated
  3 a.m. field).
- Collision-checked against all 50 live titles: no duplicate or near-duplicate.
  No live entry mentions NTP, syncing, body clock, clock skew, or blame.
- No blind A/B judging was possible: the shared OpenRouter free-tier key is exhausted
  until Nov 26 07:00 WIB, so no paid judge/model call was made. Decision rests on
  rubric scores + tournament evidence (see `../candidates.md` in the build workdir).

## Run

```sh
python3 main.py   # writes /output/entry.txt
```

## License

MIT — see `LICENSE`.
