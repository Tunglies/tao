---
"tao": patch
---

Reduce rendering stutter during macOS live resize by dispatching resize events while the window is resizing and avoiding duplicate redraw requests for the same window.
