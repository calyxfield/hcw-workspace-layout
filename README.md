# HCW Workspace Layout Prototype

A standalone layout study for the cellular-automata factory game's pseudo-desktop.

It deliberately tests the workspace shell before the game is coupled into it: launching, opening multiple independent windows of one application, moving, resizing from both lower corners and three edges, snapping, focusing, minimizing into per-window sidebar entries, restoring, maximizing, pinning, Delete-key cleanup, closing, arranging, and locally saving application windows. The System Designer now treats its grid as a fixed 1800×1200 design world viewed through a resizable camera with arrow-key panning and stepped zoom. Its component palette can detach into a linked window, leaving a functional triangular tether behind, then minimize, restore, and reattach without losing the selected component. Pinned windows survive the Delete cleanup, while Delete remains available inside text fields. Placeholder Designer, Manual, Contract, Trace, Notes, and Archive applications establish the intended spatial relationships. `WorkspaceBridge` exposes a small topic-based event surface for later window-to-window behavior.

Open `index.html` directly or visit the published GitHub Pages build.
