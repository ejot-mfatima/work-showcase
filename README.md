# Work showcase — Time Tracking · Task Management · Risk Management

Presentation of three projects on the EJOT Engineering Platform (EOS).

## Open

Open `index.html` in a browser. Everything is local (reveal.js is vendored), so it works offline.

| Key | Action |
| --- | --- |
| `→` / `Space` | Next slide — on a slide with tabs or steps (learnings), the next one |
| `←` | Previous slide, tab or step |
| Click a tab or a step | Jump straight to it |
| Click or hover a chip on a “Beyond the brief” slide | Its one-line explanation |
| Click a chapter in the footer, or press `1`–`5` | Jump to that chapter or to the status board |
| Hover a chapter in the footer | Its one-line summary and status |
| Click a chapter card or a status column | Jump to that chapter |
| `S` | Speaker view with notes and timer |
| `F` | Full screen |
| `O` | Slide overview |
| Click a screenshot | Zoom in (click or `Esc` to close) |
| Thank-you slide | Moves on its own: another screen and a topic every 7 seconds. A dot jumps to one; it waits while the mouse is over the screens |

The slides carry little text on purpose: the detail for every slide and every tab is in the speaker notes (`S`).

The footer bar shows where you are: earlier chapters are ticked, and the ring around the current chapter fills as you move through it.

## Status colours

Green = done, orange = in progress, red = not done — open, or on hold (pause mark). The three colours mean status only; the chapters use blue tones.

## Template

The slides use the EJOT master slide (red bar, claim, logo, footer line). The frame is defined once in `index.html` (`.frame`) and styled in `deck.css`; the footer text is edited there.

## Structure

1. Opening — agenda, then the four chapters at a glance with their status
2. Time Tracking — why, approach, the flow, screens per role (tabs), own additions, status
3. Task Management — approach, screens (tabs), own ideas (tabs), status
4. Risk Management — why, approach, screens (tabs), UX decisions, status
5. Versioning & Releases — how it works, in practice (tabs), status
6. Summary, status board, wins and open points, next steps and asks, learnings, questions

## PDF copy

Open `index.html?print-pdf` in Chrome and print to PDF (landscape, no margins, background graphics on). Every tab becomes its own page.

## Notes

Screenshots show local development environments with fictional sample data.
