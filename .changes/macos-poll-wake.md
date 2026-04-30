---
"tao": patch
---

Fix macOS `ControlFlow::Poll` scheduling to use a cancellable immediate wake instead of a near-zero repeating run loop timer.
