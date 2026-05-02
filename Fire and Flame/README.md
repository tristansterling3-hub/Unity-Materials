# Fire and Flame

Fire and smoke material/shader showcase.

## Flame

[Watch Flame Demo](./Flame.mp4)

### Flame Shader Breakdown

This flame graph scrolls and distorts the main flame texture, then applies dissolve masking to break up edges.

- `_Main_Texture` provides the base flame shape.
- `_Distortion_Scale`, `_Distortion_Amount`, and `_Distortion_Speed` create turbulent motion.
- `_Dissolve_Scale`, `_Dissolve_Amount`, and `_Dissolve_Speed` control flame breakup and flicker.
- `_Color` is HDR and controls glow tint/intensity.

## Smoke Effect

[Watch Smoke Demo](./Smoke%20Effect.mp4)

### Smoke Shader Breakdown

The smoke setup layers a primary texture with gradient/color shaping and animated opacity for soft volumetric-looking movement.

- `_Main_Texture` and `_Gradient` shape smoke body and falloff.
- `_Opacity` controls transparency range.
- `_Color_Intensity` shifts brightness and contrast over the smoke.
- `_Vector_1` acts as a general strength driver for distortion/fade behavior.
- `_Color` is HDR and defines final smoke/fire tint.
