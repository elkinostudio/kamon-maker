# Kamon Maker — Japanese Family Crest Generator

*by mono Japan*

Design your own Japanese family crest (*kamon*) in the browser. Pick an outer frame and a center motif, adjust size, rotation and traditional colours, read what your combination symbolizes, and download it as a 1024×1024 PNG or a scalable SVG.

**Live demo:** https://elkinostudio.github.io/kamon-maker/

![Kamon Maker on desktop](screenshot-desktop.png)

## Features

- **6 outer frames** — None, Maru (Circle), Futae-maru (Double Circle), Sumikiri-kaku (Cut-corner Square), Kikkō (Tortoise Shell), Sumitate-kaku (Diamond Square)
- **29 center motifs in 5 categories**
  - Plants: Umebachi, Kikyō, Hanabishi, Sakura, Go-san no Kiri, Mitsuba-aoi, Mitsu-ichō
  - Animals: Chidori, Chō, Usagi, Tonbo, Chigai Taka-no-ha, Kame
  - Sky & Nature: Kuyō, Ichimonji Mitsuboshi, Yukiwa, Mikazuki, Fuji
  - Objects: Chigai-ya, Igeta, Genji-guruma, Ōgi, Fundō
  - Patterns: Mitsu-uroko, Takeda-bishi, Mitsu-domoe, Wa-chigai, Yotsume-yui, Shippō
- **Size and rotation** controls
- **Traditional colour presets** plus free colour pickers, with an optional transparent background
- **Meaning & origin card** that describes your combination in English
- **Randomize** with one tap
- **Download** as PNG (1024×1024, ideal for social media icons) or SVG
- **One screen, no scrolling** — tabbed tool tray on phones, three-column workbench on desktop
- Keyboard: ← → change motif, ↑ ↓ change frame, R randomizes

## Run locally

It is a single HTML file with no build step. Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

React 18 and htm load from public CDNs (cdnjs, unpkg); fonts load from Google Fonts.

## About the meanings

The symbolic readings are traditional associations, not fixed rules. Historical notes (clans, shrines) were checked against published sources; crests you make here are original designs, not registered family mon.
