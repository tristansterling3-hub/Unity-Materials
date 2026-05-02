# Slash

Slash material/shader showcase.

## Video

[Watch Video Demo](./Slash.mp4)

## Shader Breakdown

This slash effect is driven by animated Voronoi cells that are thresholded and tinted for a sharp energy streak look.

- `_Voronoi_Scale` controls cell density/detail.
- `_Voronoi_Speed` controls animation speed.
- `_Voronoi_Power` sharpens/softens the cell breakup.
- `_Color` is HDR and controls final emissive brightness.

## Image

![Slash Preview](./Slash.png)
