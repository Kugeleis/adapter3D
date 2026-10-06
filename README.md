# Thread Adapter Generator

Real helical threads, generated in your browser. No server, no upload.

![Screenshot of the app showing a rendered thread adapter](screenshot.png)

## Usage

Open `Thread Adapter Generator.html` in any modern browser, pick the two thread sizes, and download the STL.

## Printing notes

- Print **upright**, exactly as exported (axis vertical).
- Right-hand threads with 60° flanks.
- Female threads get the radial clearance you set — start with **0.2 mm** for FDM and test-fit.
- Thread starts get a **45° lead-in chamfer** sized to the thread (one thread depth deep): male tips taper from root Ø to major Ø, female openings flare to the major Ø. Disable it with the *Chamfer thread starts* checkbox.
