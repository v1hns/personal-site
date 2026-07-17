# Project screenshots — drop-in guide

The underwater redesign shows a real screenshot inside each project's "specimen"
frame and in the featured Presonance window. Anything missing shows a labelled
placeholder telling you the exact filename to add.

## How it works
- Featured Presonance window → `presonance-desktop.png` (already captured live from presonance.tech)
- Each project card → `media/screens/<key>.png`, cropped/cover from the top.
- If a file is missing, the card shows `add media/screens/<file>` with the project icon.

## Filenames the site looks for
| Project            | File                      | Status            |
|--------------------|---------------------------|-------------------|
| Presonance (card)  | `presonance-product.png`  | captured live   |
| Presonance (hero)  | `presonance-desktop.png`  | captured live   |
| Sentinent          | `sentinent.png`           | drop in           |
| really.ai          | `really-ai.png`           | drop in           |
| Brain Stroke       | `brain-stroke.png`        | drop in           |
| OncoScan AI        | `oncoscan.png`            | drop in           |
| ISB / Comp Bio     | `isb.png`                 | drop in           |
| cloneSMP           | `clonesmp.png`            | drop in           |
| MedSim             | `medsim.png`              | drop in           |
| pixel-agents       | `pixel-agents.png`        | drop in           |
| WhatsApp Bot       | `whatsappbot2.png`        | drop in           |

## Tips
- Landscape shots (~16:10) look best; the card crops to the top of the image.
- To re-capture a live site, use any headless screenshot tool, or ask me to grab it.

## Scuba diver
Drop a transparent **`media/diver.png`** (PNG with alpha) to replace the built-in
SVG placeholder. It auto-loads — no code change needed. A side-profile diver facing
right works best (the site flips it based on swim direction).
