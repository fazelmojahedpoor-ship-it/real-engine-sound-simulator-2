# Real Engine Sound Simulator V2

A static browser prototype with a Three.js Yazd-inspired road scene and simplified driving controls.

## Important audio note
V2 still uses **procedurally synthesized Web Audio**, not licensed recordings of an actual Honda CB1300 or V10. Those sounds are approximations and are not represented as genuine recordings. This release does not include third-party engine recordings because I have not verified suitable recordings and their redistribution permissions.

## Controls
- Hold **THROTTLE** to rev / accelerate.
- Hold **CLUTCH** while moving, then tap **+ GEAR** or **− GEAR**. The clutch and shifter are separate pointer controls so the clutch can remain held while another finger taps a shifter.
- **BRAKE** slows the vehicle.
- **QUICK BLIP** gives a short rev.
- Keyboard: W/Up = throttle, S/Down = brake, Shift = clutch, E = upshift, Q = downshift, N = neutral, A/D = steer.
- Use the vehicle selector to change engine profile, **Cockpit/Exterior** to change view, **Sunset/Daylight** to change lighting, and the volume slider or **MUTE** button to adjust sound.

## Run / deploy
The page imports Three.js from a CDN, so an internet connection is required. Upload `index.html`, `README.md`, `AUDIO_CREDITS.md`, and `TEST_REPORT.md` to the root of the existing GitHub Pages repository. No build step is required.

## Limits
This is a prototype, not a physically accurate vehicle simulator. Engine characteristics, drivetrain, and speed are simplified. The visuals and sound should not be taken as accurate vehicle telemetry or authentic engine recordings.
