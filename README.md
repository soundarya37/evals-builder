# Evals Playground (Prototype)

A single-file HTML interactive companion to the "evals-for-builders" resource — a hands-on exercise for writing a first eval rubric, framed the way a product designer would critique a design rather than the way an ML engineer would run a QA gate.

## Description

This is a working-session tool, not published content. The evals-for-builders repo carries the "why" (starting with Chapter 1, "Why Evals Matter"); this playground is the "do it yourself" companion — paste a prompt and a few real outputs, build a rubric criterion by criterion, score against it, and reflect on what the exercise revealed.

Four steps:
- **Prompt & outputs** — paste the exact prompt used, then two or more real outputs it produced (not hypotheticals).
- **Build rubric** — add criteria one at a time, each with a name, a weight (low/normal/high), and a description of what a pass and a fail actually look like.
- **Score** — score every output against every named criterion (fail / partial / pass), with an optional note per score. Hesitating between pass and fail is treated as a cue to go back and sharpen the criterion's description, not just a scoring problem.
- **Summary** — a weighted pass rate per output, a per-criterion breakdown, and a reflection prompt on what building the rubric surfaced about the original prompt's intent.

All data is in-memory placeholder state — refreshing the page clears the current rubric and scores.

## Visuals

Botanical-dark theme, consistent with the rest of the build series: deep green panels on a near-black green background, parchment text, sage for the active step and "pass" scores, turmeric for weighted totals and "partial," terracotta for "fail." Fraunces for headings, Inter for body text, IBM Plex Mono for tags and labels.

## Installation

No build step. Download `evals-playground.html` and open it directly in any modern browser.

## Usage

- Step through the numbered pills at the top, or use the Next/Back buttons within each panel.
- Add or remove outputs and criteria freely — the scoring step only shows criteria with a name and outputs with text.
- Click a score button (fail/partial/pass) to score a criterion for an output; click again to change it.
- "Start a new rubric" on the summary step clears everything after a confirmation.
- Edit the CSS variables at the top of the file to adjust the color theme.

## Support

Personal prototype with no support channel. Edit the single HTML file directly to change behavior or styling.

## Roadmap

- Add persistence so a rubric and its scores survive a page reload.
- Add export (copy-as-markdown or similar) so a finished rubric can be dropped into the GitHub repo as a worked example.
- Consider linking this playground from the repo itself once it's stable enough for public use.
- Possible extension: let a rubric be saved and reused across multiple prompt/output sets.

## Contributing

Solo project for now — no external contributions expected, though this may eventually be shared publicly alongside the evals-for-builders repo.

## Authors and acknowledgment

Built by Soundarya as a hands-on companion to her evals-for-builders educational resource.

## License

Personal project — no license specified. (Note: evals-for-builders itself is CC BY 4.0 — decide separately whether this playground should match that if it's published alongside it.)

## Project status

Prototype / concept test. Not actively maintained beyond this initial pass.
