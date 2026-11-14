# Barnspek website

Part of [Barn](https://rogerbarnfather.github.io/barn-website/).

Live at <https://rogerbarnfather.github.io/barnspec-website/>.

The website for [Barnspek](https://packagist.org/packages/rmb32/barnspek): an introduction, the
philosophy, a quick start and the documentation. Static HTML, no build step; open `index.html` in a
browser. Links between pages are relative, because GitHub Pages serves a project site from a subpath.

- `assets/base/`: the shared Barn website stylesheet. An identical copy of the main site's, checked by
  `bin/ci-all` in the suite folder. Don't edit it here.
- `assets/site.css`: Barnspek's own components.
- `assets/screens/`: real captures of the tool, 2× resolution, from a disposable barn with made-up
  hotel data. `spec-map` and `spec-work` are copies of the main site's.
- `docs/style-guide.md`: this site's style guide.

Pages: `index.html` (introduction), `philosophy.html`, `quick-start.html`, and `docs/` (overview, model,
capture, read, prove, phases, gui, cli, data, glossary, troubleshooting). Every command shown was run for
real in a disposable barn with the released packages, and its output pasted in with paths and IDs
shortened by "…". Retake them when a command's output changes.

### Barnspek rename captures — 2026-11-14

Retaken from the local Barnspek core/CLI/GUI **0.1.0 candidates**, inside Barn GUI
**0.2.0 candidate**, in installed Chrome at 2× resolution. These candidates are not
published yet. Each light capture has a `-dark.webp` companion selected by the site.
Existing public image filenames and README embed URLs are retained.

- `spec-map`: Reservations at a made-up Hotel, with six stories for Guest and
  Receptionist across the five lifecycle stages. Five are planned; the receipt
  story was proven by a real Scenario Bridge run and released.
- `spec-work`: a replacement-receipt scenario whose one ticket is done, with no
  run recorded. It remains “All tickets done — not yet run”.

The map is 1408 × 780 CSS pixels and Work is 1408 × 930; the main site's home
capture is 1408 × 420. Only disposable projects were written. The local path
was hidden before capture; no screenshot wording or result was painted over.
Capture scripts, fixture records and verification are retained in the suite's
`docs/plans/barnspek-rename-stage4b/` evidence. Website destination and publication
remain pending; the existing verified site URL above is unchanged.
