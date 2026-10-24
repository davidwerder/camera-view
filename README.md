# camera-view

A single-page camera live view for the browser, made for a USB microscope camera
but works with any camera the browser sees.

- Live view fitted to the window, 1080p/60 fps or 4K/30 fps
- Switch between cameras
- Snapshot of the full frame as PNG (to Downloads)
- Fullscreen

Keys: `4` 1080p/4K, `c` next camera, `s` or space snapshot, `f` fullscreen.

Open it from the GitHub Pages address (camera access needs https). Runs in
Chrome and Edge, also Chrome on Android; an external USB camera shows up on a
phone only where Android passes it on to the browser. Nothing leaves the
device: the page has no server side and loads nothing from elsewhere.

License: MIT, see `LICENSE`.
