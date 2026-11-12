# Marrow

Live X-ray mirror. Real anatomy fitted to your face and hands in the browser. Video never leaves the device.

**Open:** https://vibe-coding-powerapps.github.io/marrow/

- Auto-fit from 478 face landmarks; jaw, gaze and blinks follow you
- Hand bones mapped onto your own tracked joints
- 3D section cuts that turn with your head, CT sweep, fingertip lens
- Expose plates (PNG) and record clips (WebM)

Anatomy of one adult; typical placement, not a scan. Not a medical tool.

## Credits
- Anatomy models: **BodyParts3D**, © 2008 Life Science Integrated Database Center, licensed under [CC BY-SA 2.1 Japan](https://creativecommons.org/licenses/by-sa/2.1/jp/deed.en). Decimated and re-aligned for this project; the derived model data in `index.html` is shared under the same license.
- Tracking: MediaPipe Tasks Vision (Apache 2.0). Rendering: three.js (MIT).
