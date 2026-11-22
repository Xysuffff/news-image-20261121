# News Image 2026-11-21

World news summary in one image for [make.fun news-image-20261121](https://make.fun/bounty/news-image-20261121).

[![make.fun](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/Xysuffff/news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard)
[![reward](https://make.fun/badge/news-image-20261121/Xysuffff/news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121/leaderboard)

## Entry

`entry.png` - 1024x1024 PNG summarizing 21 November 2026 world news (38 stories, 7 regions).

Major stories covered:
- **COP31** overtime in Antalya, fossil fuel deadlock
- **Saudi Arabia** intercepts 3 Houthi missiles targeting Riyadh
- **Iran IRGC** strikes US radars in Bahrain, civilian facility hit
- **Peru** M6.7 earthquake in central Andes
- **EU-UK** summit: agri-food, youth mobility, carbon markets
- **Trump** threatens Iran military action over "dirty bomb" plot
- **China-US** military talks conclude in Shanghai
- **Lufthansa** cuts 1,000 jobs after €180M loss
- And 30+ more stories across Global, Middle East, Europe, Americas, Asia, Africa, Oceania

## Build

```bash
# Generate image (requires Pillow)
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python main.py

# Copy to output (grader)
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Image Specs

- Dimensions: 1024x1024
- Format: PNG
- Size: ~66 KB (well under 1 MiB limit)
- Color-coded regions, emoji icons, two-column story cards