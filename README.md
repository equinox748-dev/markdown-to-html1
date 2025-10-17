# markdown-to-html

A lightweight static web app that converts a Markdown file (`input.md`) into HTML  using [marked](https://github.com/markedjs/marked).  Now enhanced with an Aria live alert that reports lookup and render status.

## Features

- Converts Markdown to HTML in-browser.
- Automatically fetches and renders `input.md`.
- Inlines SVGs for better display.
- **New in Round 2** : Accessible `github-status` live region that announces repository lookup status:
  - "Looking up repository…"
  - "Repository found!…"
  - "Failed to find repository.…"

## Accessibility

The page includes an Aria live region:

``chtml
<div id="github-status" aria-live="polite"></div>
`chtml

This ensures screen readers are notified when loading, succeeding, or failing.

## Local Use
1. Download or clone this repos.
2. Place an `input.md` file in the same directory.
3. Open `idex.html` directly in any modern browser.

## Round 1 Brief

create a index.html page that converts input.md from attachments to HTML 

using marked, renders it inside (Round 1) 

## Round 2 Brief

Show an aria-live alert `#github-status` that reports when a lookup starts, succeeds or fails.

## License

MIT License