# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML. One `index.html` with inline CSS and JS. No build step, no frameworks, no external JS. Web fonts from a single CDN are allowed, with system fallbacks. The same file is later rendered to an A4 PDF with headless Chromium, so print styles are part of the product, not an afterthought.

## Users

Senior developers who already use Claude Code and want to know which skills are worth installing. They arrive to copy an install command, check what a skill is good for, or see what a realistic prompt looks like. They scan first and read second.

## Product Purpose

"Skills I Use" is a technical reference page documenting five Claude Code skills (Impeccable, Karpathy Guidelines, Superpowers, Taste Skill, Trail of Bits Skills): how to install each, what each is good for, and one realistic example of using it. Success is a reader who can install any of the five correctly from this page alone and knows when to reach for which.

## Positioning

A first-person, verified reference. Every install command is taken from the source repo's README rather than from memory, and the page explains how the five skills fit together instead of listing them in isolation.

## Operating Context

Read on a desktop next to a terminal running Claude Code, sometimes on a phone, and also as a printed or PDF A4 document. Commands get copied straight into a shell or the Claude Code prompt.

## Capabilities and Constraints

- Quick-install block with every command and a copy button per command.
- One section per skill: one-line pitch, install commands, 3 to 5 concrete benefits, one example prompt with a short description of what happens.
- A "How they stack" section and a warning that skills can run arbitrary code.
- Sticky table of contents on desktop, collapsible on mobile.
- Light and dark mode.
- Print: A4, no sticky navigation, no copy buttons, wrapped code, no page breaks inside code blocks or skill cards, link URLs shown after link text.
- Examples are based on Next.js/TypeScript, Django, or Laravel work.
- Install commands must match each source README. Nothing invented.

## Brand Commitments

Voice: calm and editorial, like good documentation. Plain prose. No em dashes, no emojis, no marketing words such as "seamless" or "game-changer". Not a SaaS landing page. Code is shown prominently. Information density is high but easy to scan. It must not look like AI-generated UI: no purple gradients, no emoji icons, no glassmorphism, no generic hero with three feature cards.

## Evidence on Hand

READMEs and sites of the five projects, fetched on 2026-11-11. No testimonials, benchmarks, or usage numbers exist and none may be invented.

## Product Principles

1. The source README wins over memory or secondhand notes.
2. Commands first: a reader should reach a copyable command without reading prose.
3. Say what a skill is for in concrete terms, with a prompt someone would really type.
4. Screen and paper are both first-class outputs.

## Accessibility & Inclusion

Semantic HTML, visible focus states, WCAG AA contrast in both light and dark themes.
