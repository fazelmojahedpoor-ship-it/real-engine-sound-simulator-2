# V2 test report

## Checks performed
- Source changes applied to the existing V1 `index.html`.
- Verified the clutch button handler no longer treats pointer-leave as a release event; it uses pointer capture and releases on pointer-up/cancel/lost capture.
- Verified the shift function no longer has a code path that blocks a shift merely because the clutch is held. At speeds above 5 km/h, clutch must still be held to shift.
- Verified volume slider respects mute state in its handler and a mute/unmute control is present.
- Source inspection completed.

## Not tested / limitations
- Not run in a real iPhone Safari session or on an iPhone 11.
- Not tested against the live GitHub Pages deployment.
- Simultaneous multi-touch behavior has not been physically device-tested; implementation is based on Pointer Events and pointer capture.
- No authentic CB1300 or V10 recordings are included. The engine sounds remain synthetic approximations.
- Visual performance and audio quality have not been evaluated on device.
