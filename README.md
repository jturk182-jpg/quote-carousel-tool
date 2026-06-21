# Quote Carousel Tool

A single-file generator for **quote-commentary Instagram carousels** by Dr. Josh Turknett (Performance Neurology).

The format: start with a quote from another author/guest, then add depth through a neuroscience lens and JT's perspective. The quote is the door; the commentary is the value.

## Slides (6)

1. **The Quote** — punchiest fragment + attribution + a tension line that opens a question
2. **The Situation** — who said it, briefly
3. **The Principle** — what the quote reveals
4. **The Brain** — the mechanistic, neuroscience value-add
5. **The Reframe** — what it means for the viewer
6. **CTA** — punch line + action

## Usage

Open `index.html` in a browser.

- **Drafts** — load a built-in example into the editor
- **Load JSON** — paste a carousel's JSON to populate all fields
- Edit any field on the right; the preview updates live
- **Download All PNGs** — exports six 1080×1350 PNGs (zipped)
- **Copy JSON** — copies the current carousel as JSON

Body fields support `*gold*` and `**bold**` emphasis. On the Brain slide, the first `*gold*` phrase can be hand-marked (`underline` / `circle`) via the Brain-mark dropdown.

## Deploy (Netlify)

Static site, no build step. Connect this repo in Netlify with:

- **Build command:** _(none)_
- **Publish directory:** `.`

## Design

Near-black + Source Serif 4 + gold, deliberately light-touch (reads like a person's notes, not a marketing template). Built with html2canvas + JSZip (loaded from CDN).
