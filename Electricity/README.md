# Electricity

Electricity material/shader showcase.

## Preview

[Watch Video Demo](./Electricity.mp4)

## Shader Breakdown

This graph builds electric arcs from animated noise in polar UV space, then shapes it into thin streaks.

- `_Electricity_Scale` controls arc detail frequency.
- `_Electricity_Thickness` controls line thickness.
- `_Electricity_Amount` boosts overall intensity.
- `_Electricity_Speed` and `_Noise_Speed` drive directional motion.
- `_Color` is HDR and sets the final glow color.
