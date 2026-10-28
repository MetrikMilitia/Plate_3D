Plate 3D

A free, offline, Tinkercad-style 3D modeler for 3D printing. One HTML file. No account, no install, no internet.

Plate 3D runs entirely in your browser. Nothing is uploaded anywhere. Build parts from basic shapes, cut them with holes, and export them for your slicer in millimetres.

Try it online: https://metrikmilitia.github.io/Plate_3D/

Use it offline: download index.html from this repository (open the file, then use the download button for the raw file) and open it in your browser. It works with no internet connection.

What it does
Solid and hole shapes. Mark any shape as a hole, group it with a solid, and the hole is cut out. This is the same idea that makes Tinkercad easy.
Group, ungroup, intersect. Combine shapes, split a group back into its original shapes, or keep only the part where shapes overlap.
Handles for everything. White squares resize, colored dots rotate, a black arrow lifts. While you drag, you can type the exact value you want.
Exact numbers. Every size, position and rotation box accepts typed values, relative changes (+15, *2) and simple math (50/2).
Align, array, mirror, measure. Align shapes to each other or to a reference shape, make linear or circular arrays, mirror on any axis, and measure distances between points.
Rounded edges. A Radius setting rounds the edges of boxes, cylinders, cones, wedges and roofs.
Sketch, text and SVG. Extrude a typed outline, revolve a profile, make 3D text, or import an SVG and extrude it.
Reference image and tracing. Put a photo or drawing on the plate, set its real scale with two clicks, and trace its outline into a 3D shape.
Slice plane. Cut a shape in two with a movable plane.
Views. Orbit, pan and zoom to where the pointer is, switch to an orthographic (flat) view, and jump to front, top and right views. You can look at your work from underneath the plate.
Safe to work in. Undo and redo, automatic recovery copies, hide and show shapes, and an optional grid snap.
Languages. English, Italian and Spanish (use the language button).
Shapes

Box, cylinder, sphere, cone, pyramid, wedge, roof, torus, N-sided prism (hexagon and more), tube, ring, half-sphere, slot, gear, screw, hook, plus sketch and text shapes.

Import and export
	Formats
Export	STL, OBJ, 3MF (all in millimetres)
Import	STL, SVG, and your own project files (.json)

Note: OBJ keeps the Z-up orientation used in the app. Some programs expect Y-up and will show the part lying on its side.

Controls
Action	How
Select	Click. Shift+click adds more. Drag on empty space to draw a selection rectangle.
Move	Left-drag. Alt+drag lifts.
Orbit / pan / zoom	Right-drag / Shift+right-drag or middle-drag / mouse wheel (zooms toward the pointer)
Undo / redo	Ctrl+Z / Ctrl+Y
Duplicate	Ctrl+D
Group / ungroup	Ctrl+G / Shift+Ctrl+G
Align tool	L (then click a selected shape to use it as the reference)
Measure	M (click two points, Esc to leave)
Hide	H hides the selection. The "Show all" button brings everything back.
Orthographic view	O
Nudge	Arrow keys move the selection by your grid step. Shift = 10x. PgUp/PgDn moves up and down.
Delete	Del

While dragging a handle, press a number key to type the exact size. Press Enter to apply it and Esc to cancel. Hold Ctrl to keep proportions.

Your files and data
Save downloads a design.json project file to your computer. This is your real copy, so keep it somewhere safe.
Autosave also keeps a recovery copy inside your browser's own storage in case of a crash or an accidental tab close. It can be erased if you clear site data or use a private window, so do not rely on it as your only copy.
The reference image is not saved in the project. Load it again after reopening a project.
Everything stays on your computer. The app makes no network requests.
Known limits
The build plate is 2000 x 2000 mm, and shapes can sit up to 2000 mm above or below it.
Very complex shapes can make group and hole operations slow, and extremely complex ones are combined without cutting (the app tells you when this happens).
Tracing uses straight lines between your clicks, not curves.
It needs a browser with WebGL. Not every browser and graphics card combination has been tested, so please report any problems.
Check your exported file in your slicer before printing anything that matters.
License

MIT. See the LICENSE file. The software is provided as it is, with no warranty of any kind.

Reporting problems and ideas

Please open an Issue on this repository. A short description, your browser and operating system, and the steps that caused the problem help a lot. A saved design.json that shows the problem is even better.
