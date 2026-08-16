# HCW Workspace Layout Prototype

A standalone layout study for the cellular-automata factory game's pseudo-desktop.

It deliberately tests the workspace shell before the game is coupled into it: launching, moving, resizing from both lower corners and three edges, snapping, focusing, minimizing, restoring, maximizing, pinning, Delete-key cleanup, closing, arranging, and locally saving application windows. Pinned windows survive the Delete cleanup, while Delete remains available inside text fields. Placeholder Designer, Manual, Contract, Trace, Notes, and Archive applications establish the intended spatial relationships. `WorkspaceBridge` exposes a small topic-based event surface for later window-to-window behavior.

Open `index.html` directly or visit the published GitHub Pages build.
