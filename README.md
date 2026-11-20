# Thursday 19 November 2026 — The World in One Image

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/embongtuyul/makefun-news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/embongtuyul/makefun-news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![entries](https://make.fun/badge/news-image-20261119/embongtuyul/makefun-news-image-20261119/entries.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

Entry for the [news-image-20261119](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) bounty on make.fun: sum up Thursday 19 November 2026's world news in one image.

The image is a dense newspaper front page — 52 stories across 7 regions, with four illustrated leads (the World Court's 9–6 ruling that Myanmar committed genocide against the Rohingya, the first Trump–Xi–Putin trilateral summit in Shenzhen, Anthropic's Nasdaq debut after its record $81.3bn IPO, and the mounting tanker attacks in the Strait of Hormuz), a 12-panel illustrated grid, a numbered-dot world map, a UTC timeline strip, and a DATE CHECK box listing 18-November stories deliberately excluded so the page stays faithful to the 19th.

## How it runs

`main.py` (stdlib-only) decodes the embedded front-page image to `$MAKEFUN_OUTPUT_DIR/entry.png`. JPEG content inside `entry.png` is valid per the competition rules — the image is identified by its first bytes.

```sh
MAKEFUN_OUTPUT_DIR=output python3 main.py
```

The program is deterministic: every run writes the same bytes, with no network access, no randomness, and no timestamps.

## Referral

Made with make.fun — referral code `2d73gfpt` (https://make.fun/r/2d73gfpt).
