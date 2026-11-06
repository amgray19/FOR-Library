# FOR-Library

KUMC "One KU Facilities & Other Resources" boilerplate library: a single static HTML page (`index.html`) that collects the Facilities & Other Resources text investigators paste into NIH and other grant applications, grouped by collapsible sections, with a client-side export to .docx (`html-docx-js` from jsDelivr CDN).

Work project (KUMC), not Leftward Labs. Vault: KUMC-Vault (`/Volumes/web/KUMC-Vault/KUMC-Vault/`), not ClaudeVault. No LL branding, monetization, Expo, or store rules apply.

## Source of truth

- `index.html` is the live document. Imported 2026-11-06 from `~/Downloads/for-boilerplate-20261023.html` (version dated 2026-10-23).
- Edits are made here and committed; the published copy is whatever KUMC hosts. Record where it is hosted in `docs/publishing.md` once known.

## Rules

- Contents are institutional text with KUMC contact emails. No public remote, no pushes to GitHub, no copies to third-party services without Andrew's explicit OK.
- Keep the page self-contained: one file, no build step. Prefer CSS and plain JS over dependencies.
- Preserve KU brand colors already in the page (`#0051BA` blue, `#DB000B` red, Raleway headings, Arial 11pt body).
- US English. Do not rewrite boilerplate prose voice; facilities text is owner-supplied by each core or department.

## Quirks

- The file opens with two `<!DOCTYPE html>` lines and two `<title>` elements. Harmless in browsers; clean up only as a deliberate change.
- Lines are very long (36k chars); use targeted search, not full reads.

## Session protocol

Daily file: `.claude/today/YYYY-MM-DD_FORLibrary.md`. `PROGRESS.md` holds verified task state.
