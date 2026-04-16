# Copilot Instructions

This repository contains a single-page static Todo list app implemented in `index.html`.

## Key facts
- `index.html` is the only source file.
- No build tools, package managers, or test framework are present.
- The app uses inline JavaScript and CSS inside the HTML.

## What to do
- Make edits directly in `index.html`.
- Prefer simple, vanilla HTML/CSS/JS changes.
- Preserve the existing Japanese UI and text where possible.

## What to avoid
- Do not introduce frameworks, bundlers, or build pipelines.
- Do not assume there is a backend or database.
- Do not create a new project structure unless the user explicitly requests it.

## Known issue
- `index.html` currently attaches `input.addEventListener("keypress", ...)` outside of any `input` variable scope. An agent should address this when editing event handling.

## Notes for "auto save"
- This project does not currently implement auto-save behavior.
- Any feature requests for auto-save should be handled in the context of the static page, for example using local storage or page state persistence.
