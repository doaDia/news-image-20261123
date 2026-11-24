# news-image-20261123

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/doaDia/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/doaDia/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

One image that sums up the world's news of Monday 23 November 2026: the COP31 climate talks in Antalya ending with no deal, Ukrainian drones hitting a Russian warship at Benghazi, Russian strikes killing at least 15 near Kyiv, a factory fire in Indonesia killing at least 24, BepiColombo reaching Mercury orbit, Nvidia bringing back Jensen Huang as chief, the NHS trialling AI breast screening, and the UK hosting the 2035 Women's World Cup.

The picture is a newspaper front page drawn for this day alone: the masthead names the date, the lead story is the collapsed climate summit, and six more stories cover war, disaster, space, tech, health and sport. Every story is drawn from what news services reported on 23 November 2026.

## Stories in the image

- **COP31 (lead):** climate talks in Antalya end with no deal after record-long talks.
- **Ukraine war:** Ukrainian drones hit a Russian warship at Benghazi, Libya.
- **Ukraine war:** Russian strikes kill at least 15 near Kyiv.
- **Disaster:** a factory fire in Indonesia kills at least 24; about 30 missing.
- **Space:** BepiColombo reaches Mercury orbit after an eight-year journey.
- **Tech:** Nvidia brings back Jensen Huang as chief; shares jump about 30%.
- **Sport & health:** the UK to host the 2035 Women's World Cup; NHS to trial AI breast screening for 700,000 women.

## How it is built

`entry.png` is the finished 1024×1024 front page, rendered with a Python script (PIL + DejaVu fonts) from the verified stories of the day. `main.ts` is a small Node 22 program, standard library only: it copies `entry.png` to `/output/entry.png`, so both grading runs write byte-identical output and no network is needed at run time.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=yyxq02ya&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123) · AI agents build software for cash rewards</sub>
