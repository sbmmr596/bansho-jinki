# 万象陣記 full-body standee standard

Canvas: `1088×1543` (RGBA, transparent BG for final art)

## Framing (battlefield balance)
- Head tip ≈ `2%` from top
- Feet on `98%` line
- Figure vertical fill ≈ `96%` (match Kuro/Maki, not ~82%)
- Side margin ≥ `3%` each side; hair/weapon tips inside

## Proportions (Shinra Bansho Choco target)
- ~5-head silhouette inside the figure box
- Heavy outlines, hard cel-shading; props fully inside frame

## Pipeline
1. Generate on solid chroma green `#00FF00` (avoid rembg shoulder holes)
2. Chroma-key → crop → fit to this mannequin box
3. Save `chars/id.png`; bust from upper ~50–55% → `cards/id.jpg`

See `ref/mannequin.png`.
