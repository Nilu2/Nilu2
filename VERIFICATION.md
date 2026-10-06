# Verification Report

Verified on 06 Oct 2026.

## Rendering and animation
- 5 SVGs rendered as actual `<img>` elements at **0, 2, 5, 9 and 13 seconds**: 25 timed captures total.
- 5 additional SVG copies were rendered with SMIL/CSS animation removed.
- Desktop README-width preview rendered successfully.
- Mobile-width preview rendered at 390 px with `prefers-reduced-motion: reduce`.
- Browser console errors: **0**.
- External HTTP/HTTPS asset requests during render: **0**.

## GitHub-safe checks
- SVG XML parse: PASS for all 5 files.
- JavaScript: none.
- `foreignObject`: none.
- External image/font fetches inside SVGs: none.
- CSS/SMIL only; all SMIL begins at `0s` and uses `keyTimes`.
- CSS entrance animations use fill mode `both`.
- Reduced-motion static fallbacks are included.
- All 5 README image paths are relative and end in `?v=1`.
- No contribution-city section is present.

## Portrait integrity
- `assets/id.png`: RGBA, 1122×1402, true alpha range 0–255.
- `assets/right_pointing.png`: RGBA, 1122×1402, true alpha range 0–255.
- Exact source PNG bytes are base64-inlined into the relevant SVGs; SHA-256 equality was checked.
- No face redraw, tracing, silhouette mask, or external portrait request is used by the SVGs.

## Links and public data
- Supplied public profile: `https://github.com/Nilu2`.
- Other social links were omitted as requested.
- `RND Automation Inventory Software` is listed without a repository link because none was supplied.
- ID dashboard uses only dated values visible on the public GitHub profile on 06 Oct 2026: 16 repositories, 15 starred repositories, 0 followers, 2 following, plus visible popular-repository names/languages.

## QA captures
The `_verification/` directory contains the timed screenshots, static screenshots, desktop preview, mobile/reduced-motion preview, and browser request report. It is **not required** for the GitHub profile itself.
