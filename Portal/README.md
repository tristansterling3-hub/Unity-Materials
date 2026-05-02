# Portal

Portal material/shader showcase.

## Preview

<video src="./Portal.mp4" controls muted loop playsinline width="960"></video>

## Shader Breakdown

This portal graph uses UV twirl distortion plus dissolve and masking to create a spinning energy surface.

- `_Twirl_Strength` controls swirl curvature.
- `_Twirl_Speed` controls spin rate.
- `_Scale` changes noise/distortion frequency.
- `_Dissolve_Amount` erodes the portal edge/interior pattern.
- `_Strength` amplifies brightness and effect intensity.
- `_Color` is HDR and sets the portal glow hue.
