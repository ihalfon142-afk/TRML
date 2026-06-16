# TRML — Black Hole Dashboard background

Greyscale-optimized PNGs for the [Black Hole Dashboard](https://github.com/ihalfon142-afk/TRML) Private Plugin on a TRMNL e-ink display.

## Files

| File | Resolution | Use |
|---|---|---|
| `output/background_latest.png` | 800×480 | TRMNL OG, TRMNL X (downscaled), default |
| `output/background_800x480.png` | 800×480 | same as above, identical file |
| `output/background_1872x1404.png` | 1872×1404 | TRMNL X native resolution |

## Raw URLs

Use these directly in the Private Plugin's `background_url` form field:

```
https://raw.githubusercontent.com/ihalfon142-afk/TRML/main/output/background_latest.png
https://raw.githubusercontent.com/ihalfon142-afk/TRML/main/output/background_800x480.png
https://raw.githubusercontent.com/ihalfon142-afk/TRML/main/output/background_1872x1404.png
```

## Source

Source PNG (3840×2160) and the Python optimizer that produced these files
live in a separate project (`C:\Users\chech\Documents\Wallpapers\trmnl\`).
This repo just hosts the e-ink-optimized variants.

## Regenerating

```bash
# From the source project dir:
python background.py
# Then copy output/background_latest.png (and friends) here.
```
