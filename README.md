# HoloBench HUD

A holographic heads-up display drawn over your live webcam feed. Load a CAD assembly and handle it with hand gestures.

Open `index.html` in Chrome or Edge and allow the camera. It needs an internet connection to load three.js and MediaPipe hand tracking.

## Gestures

- Two hands apart / together: explode / close the assembly
- Two hands turning: rotate the assembly
- Pinch on a part: pick it and move it
- One cupped hand turning: rotate the selected part
- Pinch a part into the Part Bay and release: isolate it (a placeholder stays in the assembly)
- Pinch on a panel or button: click it

Mouse fallback: drag to rotate, scroll to explode, drag a part to move it, shift-drag to rotate the selected part.

## CAD formats

STEP/STP, GLB, OBJ, STL. Explosion needs separate bodies, so an STL loads as a single part.

The weather, calendar and to-do panels show sample data.
