---
version: 1
slug: "index-html"
primary_target: "index.html"
related_targets: []
---

# Surface brief: index.html ("Skills I Use")

Scope: one static reference page, later rendered to A4 PDF. Visitor mode: Read.
Audience and job: senior developers using Claude Code who want to copy an install command, check what a skill is for, and see one realistic prompt.
Content: intro, quick-install table, five skill sections (pitch, install, 3 to 5 benefits, example), "How they stack" with an inline SVG, a safety note.
Constraints: single file, inline CSS and JS, no external JS, one font CDN, light and dark, print styles for A4, WCAG AA.
Unresolved: none.

## Direction contract

THESIS: Five skills are five lines on one small network. The page is that network's timetable: a route colour per skill, numbered stops, ruled tables of commands. It refuses the docs-site default of a grey sidebar, rounded dark code cards and a hero.

OWN-WORLD: Uncoated timetable stock ground (cool off-white; near-black in dark mode), near-black ink, hairline and 2px rules, no card shadows, no rounded panels. Five route colours (vermilion, amber, blue, green, brown) appear only as bands, stop markers and line numbers, never as fills behind running text. Archivo with its width axis: condensed uppercase for labels, condensed title case for openers, normal width for reading. JetBrains Mono for commands. Tabular rows with copy controls set as small ruled labels, extended to a 44px hit area on touch.

STORY: The reader sees what the five skills are, copies a command within the first screen, then rides down one line at a time: pitch, install, benefits, example. The network map near the end shows which lines interchange.

FIRST VIEWPORT: 56px masthead with five colour bands and the title. Left 300px rail: contents drawn as a vertical line with five coloured stops and smaller unnumbered stops. Main column: condensed 76px title, short intro with the install paths, then the quick-install timetable (line number disc, skill, step, command, run in, copy). Main route for all five lines first, then every other route and setup command beneath, always visible.

SIGNATURE: one rail. The contents line tracks reading position (the current stop fills), and each section hangs off a route band in its line colour. The "How they stack" figure is a network diagram: two interchanges where paired lines leave and rejoin the trunk, then a single-line check stop, matching the user's own three-stage description. Motion: only the stop fill and copy confirmation.

FORM: printed transit timetable and network diagram, position 7 of 7 on the grounded list. seed:c50ba15acfd8c7db

FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance
