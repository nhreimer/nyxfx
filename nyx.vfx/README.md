
# Changelog

## 61ec1d3 (2026-01-20)

* removed LineMaskPreShader
* added LineDensityFieldPreShader
* updated DensityFieldPreShader
* updated VelocityFieldPreShader to use actual history
* add better history for line (energy & positions)
* updated both line & particle histories for longer memory
* added Nebula Shader for testing dust idea
* CurvedLines now responsible for its own history
* updated VeloctyFieldPreShader to remove gating
* VelocityFieldPreShader can use decay now
* Added NebulaDriftShader
* Colors now bleed through in density PreShaders
* EmptyShader now works with colors
* EmptyShader renamed to PassthroughShader
* NebulaDriftShader takes full advantage of PreShaders
* NebulaDriftShader uses swirl
* NoiseWarpShader doesn't use by velBoost b/c it's too hard to use
* TransformShader updated
* Added rendering priority to menu

## 7279b17 (2026-01-12)

- Fixed NoiseWarp serialization/deserialization bug
- Fixed Ripple shader position not being taken into account
- Fixed Cumulative easing serialization bug used in Glitch
- Removed PreShader automation slots

## 69dd2bd (2026-01-05)
