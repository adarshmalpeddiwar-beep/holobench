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

## Voice

Click **Enable voice** (or press V) once. The assistant, Holo, speaks in a browser voice and listens through your microphone (Chrome or Edge). Say "Holo" first, then a command:

- explode, assemble, reset the view, rotate left / right / up / down
- show / close the weather, calendar, to-do, assembly or system panel, or all panels
- what's the weather, what's on my calendar, read my tasks, complete task three
- isolate planet gear two, select the sun gear, return the part
- how many parts, system status, what time is it, help, stop

You can also type a command in the box at the bottom. Speech recognition in Chrome is processed by Google's online service. Spoken replies use your browser's installed voices, so the voice differs by device.
