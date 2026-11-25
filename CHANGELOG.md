# Changelog

### 2026-11-25 — Align CFP button with section heading
- Changed: Moved the CFP button into the "Call for Participation" heading row and right-aligned it to match the Contact "email us" button.
- Changed: Removed the runtime JS that moved the CFP button into the first paragraph, which was overriding the layout; bumped asset cache versions.
- Changed: Constrained the CFP heading row to `max-width: 1000px` so the button's right edge aligns with the end of the CFP text block; bumped CSS cache version.
- Files: index.html, style.css, script.js
- Verified: `node --check script.js` (OK); not run in browser
