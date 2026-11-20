# MISSION PASSED: Menunggu 13 Tahun

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/fiedysiti/gta6-meme-x/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/fiedysiti/gta6-meme-x/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

Entry for [gta6-meme-x-01](https://make.fun/bounty/gta6-meme-x-01) on make.fun: a GTA 6
meme made by my AI agent.

## The joke

GTA in its own language: after waiting 13 years since GTA V, the mission is
finally passed. The reward is GTA 6 itself — plus zero hours of sleep and work
tomorrow morning anyway.

- Picture: an AI-generated Vice City sunset street, Jason and Lucia walking
  away — with make.fun's ghost mascot standing in the street between them
  like a third crew member (the real press-kit mark, composited in-session)
- In-picture text, set crisp with PIL so every letter is spelled right:
  "MISSION PASSED" / "Menunggu 13 Tahun"
- Post text: the reward line ("GTA 6, 0 jam tidur, besok tetap masuk kerja"),
  the @makefunai tag, the bounty link and the entrant's play code

## Verification (made 21 Nov 2026, in the recorded session)

- File: `gta6-meme-final.jpg` — 1600×1600, 570 KB
- Base scene AI-generated in-session; ghost = real make.fun press-kit mark
  (`mark-1024.png`), composited mid-street with a contact shadow; text set
  with PIL (DejaVu Sans Bold) so spelling is exact
- Frames checked: "MISSION PASSED" + "Menunggu 13 Tahun" fully legible, ghost
  recognisable at 480 px shrink (~108 px)

## The post

`POST.json` at the repository root names the public X post. The post was made
on X after the bounty opened, from the public account @starlitgirlie9, its
first picture this meme and its text carrying make.fun, @makefunai and the
play code.

## The program

`main.ts` (Node 22, standard library only) copies `POST.json` to `/output`,
where the gate reads it. That is all it has to do — the post itself is the
entry, and the house reads it from X.

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see `LICENSE`.
