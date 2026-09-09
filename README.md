# ghaz.amin Poetry Studio V4

A client-side poetry poster studio for GitHub Pages.

## V4 fixes
- All controls use explicit event handlers and element IDs.
- No reliance on browser-created global variables such as `export`, `title`, or `poem`.
- PNG export uses a real canvas and `toBlob()`.
- Upload, sample photo, clear, format, typography, image controls, archive, undo/redo, and drag controls are wired.
- Service worker cache bumped to v6.

Upload all files in this folder to the repository root and overwrite the old versions.
