# Just Floaty — Project Instructions for Claude

This file is automatically read by Claude Code at the start of every session in
this project. It contains the permanent rules for how to work on Just Floaty.
Follow it every time, without being reminded.

## About the human collaborator

The project owner is a complete beginner who does not write code. Claude writes
all code. Always explain technical concepts in plain, beginner-friendly
language. If a technical term is unavoidable, explain it in one sentence.
When multiple solutions exist, recommend the simplest one first.

## Required workflow before implementing anything

Before writing or changing any code, always:

1. Explain your understanding of the request.
2. Create a short implementation plan.
3. Explain the reasoning in simple language.
4. Ask for explicit approval.
5. Only after approval, start implementing.

Never skip these steps, no matter how small the change seems.

## Hard rules

- Never assume features that were not explicitly requested.
- Never add functionality beyond what was asked.
- Never redesign something unless explicitly asked.
- Never "improve" artwork on your own judgment.
- Never make creative decisions for the project owner — present options and
  let them decide.
- Always preserve existing style unless explicitly asked to change it.
- The supplied Floaty artwork must never be redrawn, generated, enhanced,
  smoothed, beautified, or replaced. Reference/use the files as supplied only.
- Do not initialize Git or run Git commands until explicitly approved.
- Do not choose a hosting provider or deploy until explicitly approved.

## Development philosophy

Simplicity over complexity. Readability over cleverness. Long-term
maintainability. Mobile-first. Accessibility matters. Performance matters.
Never over-engineer.

## Technical approach

- Plain HTML and CSS. No frameworks, no build tools, no JavaScript unless a
  future feature genuinely requires it.
- No external fonts — system fonts only.
- Mobile-first CSS, tested to work well on phones, tablets, laptops, and
  large desktop screens.
- The site must feel quiet, dry, handmade, slightly strange, and
  intentionally unfinished. It must NOT resemble a startup landing page, a
  typical cryptocurrency website, an AI-generated website, a polished
  corporate brand, or a modern template.

## Project overview

Just Floaty is a small creative character project centered on a hand-drawn
capybara character, internally nicknamed "Floaty" (no official public name).
The project publishes dry, understated, never-explained illustrations and
memes. The first product is a very small public website at justfloaty.com.

Already exists (owned by the project owner, outside this folder for now):
- The domain justfloaty.com
- Original hand-drawn character artwork
- A clear visual and humor concept
- The phrase "Still floating."
- A static loading bar concept fixed permanently at 87%

## Version 1 scope

Version 1 must remain extremely small:

- One mostly white or subtly off-white page
- A lot of empty space
- One hand-drawn illustration of Floaty sitting with his knees pulled up,
  staring blankly into space
- A static loading bar fixed at exactly 87%
- The text "Still floating."
- Possibly one discreet link to X, added later

Explicitly NOT in v1: animation, a menu, marketing copy, page sections,
cryptocurrency information, analytics, cookies, a contact form, a
newsletter, external fonts, or any functionality beyond what is listed above.

## Possible future growth (do not build yet)

These may be added later, only when explicitly requested:
- Links to X and other community channels
- A small gallery or archive of illustrations
- Information about a future coin
- A contract address with a copy button

The project should stay organized cleanly enough that these can be added
later without a rebuild, but none of them should be built preemptively.

## Hosting

Simple, inexpensive or free hosting with HTTPS is preferred. Do not choose a
provider — present the simplest suitable options and let the project owner
decide, only when asked.
