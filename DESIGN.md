---
name: Skills I Use
description: A reference to five Claude Code skills, set as a printed transit timetable and network diagram.
colors:
  line-vermilion: "#d4351c"
  line-amber: "#b08400"
  line-blue: "#0b5cad"
  line-green: "#1c7c54"
  line-brown: "#7b4a1e"
  on-line: "#ffffff"
  on-line-amber: "#15181b"
  paper: "#f1f3f4"
  ink: "#15181b"
  muted: "#4d5257"
  rule: "#c2c7ca"
  code: "#e3e7e9"
  line-vermilion-dark: "#ff6a4d"
  line-amber-dark: "#f2b900"
  line-blue-dark: "#5aa9f0"
  line-green-dark: "#4cc08a"
  line-brown-dark: "#cf9a63"
  on-line-dark: "#121416"
  paper-dark: "#121416"
  ink-dark: "#ecebe4"
  muted-dark: "#a8acb0"
  rule-dark: "#383c41"
  code-dark: "#1e2125"
  paper-print: "#ffffff"
  ink-print: "#111111"
  muted-print: "#444444"
  rule-print: "#bbbbbb"
  code-print: "#eeeeee"
typography:
  display:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(44px, 6.2vw, 76px)"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "-0.01em"
    fontVariation: "'wdth' 70"
  headline-line:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(32px, 4vw, 44px)"
    fontWeight: 800
    lineHeight: 1
    fontVariation: "'wdth' 72"
  headline:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "30px"
    fontWeight: 800
    lineHeight: 1.1
    fontVariation: "'wdth' 75"
  title:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 800
    lineHeight: 1.5
    fontVariation: "'wdth' 75"
  pitch:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "19px"
    fontWeight: 400
    lineHeight: 1.45
  lead:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.6
  body:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.6
  body-small:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.5
  note:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.6
  subhead:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "13px"
    fontWeight: 700
    letterSpacing: "0.09em"
    fontVariation: "'wdth' 75"
  label:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "12px"
    fontWeight: 700
    letterSpacing: "0.09em"
    fontVariation: "'wdth' 75"
  numeral:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "13px"
    fontWeight: 700
    lineHeight: 1
    fontFeature: "'tnum'"
  numeral-large:
    fontFamily: "Archivo, system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "20px"
    fontWeight: 800
    lineHeight: 1
    fontFeature: "'tnum'"
  code:
    fontFamily: "JetBrains Mono, ui-monospace, SFMono-Regular, Menlo, Consolas, Liberation Mono, monospace"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.5
rounded:
  none: "0px"
  stop: "50%"
  interchange: "11px"
spacing:
  column: "16px"
  subsection: "30px"
  section: "64px"
  line: "72px"
  line-phone: "56px"
  gutter-desktop: "72px"
  gutter-tablet: "40px"
  gutter-phone: "20px"
  masthead-gutter: "48px"
components:
  copy-control:
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "2px 8px"
    height: "26px"
    width: "60px"
  copy-control-hover:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
  copy-control-done:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
  theme-toggle:
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "5px 10px"
    height: "30px"
  theme-toggle-hover:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
  line-disc:
    backgroundColor: "{colors.line-vermilion}"
    textColor: "{colors.on-line}"
    typography: "{typography.numeral}"
    rounded: "{rounded.stop}"
    size: "26px"
  line-disc-amber:
    backgroundColor: "{colors.line-amber}"
    textColor: "{colors.on-line-amber}"
    typography: "{typography.numeral}"
    rounded: "{rounded.stop}"
    size: "26px"
  line-disc-opener:
    backgroundColor: "{colors.line-vermilion}"
    textColor: "{colors.on-line}"
    typography: "{typography.numeral-large}"
    rounded: "{rounded.stop}"
    size: "40px"
  line-band:
    backgroundColor: "{colors.line-vermilion}"
    rounded: "{rounded.none}"
    height: "10px"
  command-row:
    textColor: "{colors.ink}"
    typography: "{typography.code}"
    padding: "5px 0"
    height: "40px"
  table-cell:
    textColor: "{colors.ink}"
    typography: "{typography.body-small}"
    padding: "9px 16px 9px 0"
  inline-code:
    backgroundColor: "{colors.code}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "1px 5px"
  prompt-block:
    backgroundColor: "{colors.code}"
    textColor: "{colors.ink}"
    typography: "{typography.code}"
    rounded: "{rounded.none}"
    padding: "14px 16px"
  notice:
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "18px 22px 20px"
---

# Design System: Skills I Use

## Overview

**Creative North Star: "The Line Timetable"**

The system is a printed transit timetable and the network diagram bound in with it. Each subject is a line on one small network: it owns a route colour, a number and a place on the map. Information sits on uncoated stock in near-black ink, held in ruled tables, and the reader moves down it one stop at a time.

Density is high and scannable. Structure comes from rules, columns and tabular figures, so the page reads the way a timetable reads: find the row, follow it across. Commands are the primary content and get the same ruled row treatment as departures. Colour is scarce and always means which line you are on.

The same system renders on screen, in dark mode and on A4 paper. Paper is a first-class output with its own token set. The system refuses the docs-site default of a tinted sidebar, rounded dark code cards and a hero, and it carries the product's standing refusal of purple gradients, emoji icons, glassmorphism and three-card feature rows.

**Key Characteristics:**
- Flat stock, no shadows, hierarchy from rule weight alone
- Five route colours used only as bands, stop markers and line numbers
- One variable sans whose width axis does the work of a second typeface
- Square corners everywhere except the network's own stops and interchanges
- Motion limited to the current stop filling

## Colors

Cool neutral stock and near-black ink carry everything; five saturated route colours identify lines and nothing else.

### Primary
The five route colours are peers. Each is assigned to one line and stays with it across the masthead, contents, section band, line number and network diagram.

- **Signal Vermilion** (#d4351c, dark #ff6a4d): Line 1.
- **Timetable Amber** (#b08400, dark #f2b900): Line 2. The only route colour that takes ink numerals in light mode (#15181b), because white fails on it.
- **Route Blue** (#0b5cad, dark #5aa9f0): Line 3.
- **Junction Green** (#1c7c54, dark #4cc08a): Line 4.
- **Ballast Brown** (#7b4a1e, dark #cf9a63): Line 5.
- **Numeral on Line** (#ffffff, dark #121416): Line numbers on discs. Every disc in dark mode takes the dark paper colour.

### Neutral
- **Timetable Stock** (#f1f3f4, dark #121416, print #ffffff): The ground. One flat colour, with no tinted regions for navigation.
- **Press Ink** (#15181b, dark #ecebe4, print #111111): Text, the trunk line, structural rules, control borders, focus rings and selection.
- **Second Impression** (#4d5257, dark #a8acb0, print #444444): Column headers, run-in cells, notes, source links and secondary stop text. Holds at least 6.3:1 on stock and on the code tint in every theme.
- **Hairline** (#c2c7ca, dark #383c41, print #bbbbbb): Row dividers inside a group and the rail divider. Never used for text.
- **Code Tint** (#e3e7e9, dark #1e2125, print #eeeeee): The one neutral fill, behind inline code and example prompts.

### Named Rules
**The Route Colour Is Not Ink Rule.** Route colours appear only as bands, stop markers, square list markers, network segments and line-number discs. They are never a text colour, because amber and vermilion fall below 4.5:1 on light stock, and never a ground for reading text. A line numeral on its disc is the only text a route colour carries.

**The One Line One Colour Rule.** A route colour identifies exactly one line and means nothing else: no status, no emphasis, no links. Warnings are set in ink.

**The Three Sets Rule.** Every neutral and route colour is defined for light and dark, and every neutral again for print. Print keeps the light route colours and forces them to render with exact colour adjustment.

## Typography

**Display Font:** Archivo, variable on width 62 to 125 and weight 400 to 800 (with system-ui and Helvetica Neue, Arial fallbacks)
**Body Font:** Archivo at normal width
**Label/Mono Font:** JetBrains Mono at 400 and 600 for commands (with ui-monospace, Menlo, Consolas fallbacks)

**Character:** One grotesque stretched across its width axis, tight and heavy for openers, compressed and tracked for labels, normal for reading, in the manner of timetable setting. The mono is reserved for anything a reader might paste.

### Hierarchy
- **Display** (800, clamp 44px to 76px, 0.95, width 70%): The page title only, title case, balanced wrap.
- **Headline Line** (800, clamp 32px to 44px, 1, width 72%): The name of a line, beside its disc.
- **Headline** (800, 30px, 1.1, width 75%): Unnumbered sections. The boxed notice steps down to 26px.
- **Title** (800, 18px, width 75%): Stage names in the network figure and its captions.
- **Pitch** (400, 19px, 1.45): The one-line statement opening a line, capped at 68ch.
- **Lead** (400, 17px, 1.6): Introductory paragraphs, capped at 68ch.
- **Body** (400, 16px, 1.6): Running text, capped at 68ch. Inline emphasis and row names are 650, not 700.
- **Body Small** (400, 15px, 1.5): Table cells, benefit rows, numbered steps and stage descriptions.
- **Note** (400, 14px, 1.6): Muted notes, source links and the footer. Run-in cells and command hints drop to 13px.
- **Subhead** (700, 13px, 0.09em, uppercase, width 75%): Groups within a line.
- **Label** (700, 12px, 0.09em, uppercase, width 75%): Column headers, step names, control text and running-head metadata.
- **Numeral** (700, 13px, tabular; 800, 20px at opener size): Line numbers on discs.
- **Code** (400, 14px, 1.5, JetBrains Mono): Commands, prewrapped and breakable. Inline code is 0.875em of its context.

Print rescales in points: body 10pt at 1.45, display 38pt, lead 11pt, pitch 12pt, small text 9.5pt, code 8.5pt.

### Named Rules
**The Width Before Weight Rule.** Hierarchy is set on the width axis first. Condensed means a label or an opener; normal width means read this. Do not condense reading text or set labels at normal width.

**The Pasteable Is Mono Rule.** JetBrains Mono marks only commands, paths, prompts and identifiers. Explanations of a command, including hints inside a command cell, return to Archivo.

**The Tabular Figures Rule.** Tables and line numbers use tabular numerals so figures align down a column.

## Layout

A fixed 300px contents rail beside a fluid main column, separated by one hairline. The rail is sticky and the main column pads 44px top, 72px sides, 96px bottom; its children stop at 1000px and reading text stops at 68ch. A 56px masthead with a 2px ink rule runs across both.

Rhythm is vertical and ruled: 64px between unnumbered sections, 72px between lines, 30px above a subhead. Rows are compact, with a 40px minimum command row and 9px table cell padding. Columns are real grids with fixed widths for the short fields (64px step, 84px run-in) and a fluid command column between them; the timetable adds a 176px line-name column.

At 1240px and below, gutters tighten to 40px and timetable rows stack with the column header removed. At 960px and below, the rail becomes a sticky collapsible bar naming the current stop, gutters drop to 20px, command rows reflow to a metadata line above a full-width command, and two-column lists go to one. At 700px and below, wide diagrams are replaced by a vertical drawing of the same network.

Print is A4 with 16mm, 15mm and 18mm margins. The rail and all controls are removed, the column caps lift, each line starts a new page with a 6pt band, commands, rows and figures do not split across pages, and external link URLs are printed after their text.

## Elevation & Depth

There is no elevation. The system has no box shadows, gradients, blurs or layering effects; every surface is the same sheet of stock. Hierarchy is conveyed by the weight of the rule above a thing.

### Named Rules
**The Rule Weight Ladder Rule.** Four weights, each with one job: a 1px hairline divides rows within a group, a 1px ink rule opens or closes a table or group, a 2px ink rule opens a section or frames the page, and a 10px route band opens a line. Do not add intermediate weights. Drawn route lines in navigation and diagrams are track, not rules, and keep their own weights.

**The Flat Stock Rule.** Surfaces never lift. Hover inverts a control to ink; it does not raise it.

## Shapes

Corners are square by default (0px): controls, code tints, tables, the notice box and bands. Roundness belongs to the network: stops and line discs are full circles (50%), interchanges are capsules drawn with an 11px radius across two lines, and diagram segments have round caps. List markers are 7px squares in the route colour, or a 7px by 2px dash in ink inside the notice.

## Components

### Buttons
Small ruled labels, closer to a table cell than to a call to action.

- **Shape:** Square corners (0px) with a 1px ink border and no fill.
- **Copy control:** Label type, 26px minimum height, 60px minimum width, padding 2px 8px.
- **Theme toggle:** The same treatment at 30px minimum height, padding 5px 10px.
- **Hover / Focus:** Hover inverts to an ink fill with paper text, with no transition. Focus is a global 2px ink outline at 2px offset.
- **Confirmation:** The copy control inverts and reads "Copied" for 1.6s, announced through a polite live region. If the clipboard fails it reads "Selected" for 4s and selects the command.
- **Hit area:** At 960px and below, an invisible extension brings controls to 44px tall without changing how they look.

### Navigation
The contents are drawn as a route: a 4px ink line with stops hanging from it. Ordinary stops are 12px with a 3px ink border and paper centre. Line stops are 14px with a 4px border in the route colour, with a bold name and a muted descriptor. The current stop fills solid and its name takes a 2px underline. The fill is the system's only transition (150ms ease-out, removed under reduced motion).

### Line Disc
A filled circle in the route colour carrying the line number: 26px in tables, 40px beside a line's name, 20px in diagram keys.

### Line Opener
A 10px route band across the full column, then the disc, the line's name and a muted source link pushed right. The pitch follows beneath.

### Command Row
The timetable's unit: step label, command in mono, run-in cell, copy control, on one vertically centred grid with a hairline under it. A group opens with a 1px ink rule. The command itself has no fill, because the row's rules are its container.

### Tables and Ruled Lists
Text tables open with a 1px ink rule and use hairlines between rows, with muted label-type column headers and 650-weight row headers. Benefit lists use the same ruling in two columns with square route markers.

### Example Prompt
A flat band of code tint, square-cornered, holding a prompt preceded by a muted ">" and a copy control. An explanation sits below it, and 1px ink rules close the unit above and below.

### Notice
The one fully boxed element: a 2px ink frame, padding 18px 22px 20px, no fill and no route colour. Its rarity is what marks it as a warning.

### Network Diagram
Inline SVG. A 2px ink trunk runs from an open terminus to a filled one. 10px route segments leave and rejoin it, passing through paper-filled interchanges with 3px ink outlines. Station names use Title type, terminus names use label type, and a key pairs discs with line names. All strokes use the live tokens, so it follows theme and print.

## Do's and Don'ts

### Do:
- **Do** give every new line a route colour, a number and a disc, and carry that colour through its band, stop and diagram segment.
- **Do** define any new route colour for light and dark, with a numeral colour reaching at least 4.5:1 on it in both.
- **Do** choose rule weight from the ladder: 1px hairline, 1px ink, 2px ink, 10px band.
- **Do** set commands in ruled rows with a copy control, and print them wrapped and unbroken across pages.
- **Do** use uppercase condensed labels to name columns, steps, groups and controls.
- **Do** keep circles and capsules for stops, discs and interchanges.
- **Do** check every new surface on A4 as well as in both screen themes.

### Don't:
- **Don't** use a route colour for text, links, status or as a ground behind reading text.
- **Don't** add box shadows, gradients, blurs or glassmorphism.
- **Don't** round panels, controls, code tints or tables.
- **Don't** set code in dark rounded cards, or tint the navigation rail.
- **Don't** add a hero with feature cards, purple gradients or emoji icons.
- **Don't** place small uppercase kickers above headings; a label must name a column, step, group or control, or carry document metadata in the masthead.
- **Don't** animate anything beyond the current stop filling, which is the only transition; the copy confirmation is an immediate state change.
- **Don't** box content with a full frame unless it is a safety notice.
