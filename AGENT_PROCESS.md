# Agent Process Log

## 2026-07-20 — Bring site back up + publications

### Context
- Site was taken offline (`index.html` replaced with maintenance stub in commit `9fc6c8d`).
- ICML paper (DecAEvolve) was already on publications page from earlier work, but incomplete (authors listed as "et al.", no links).

### Actions
1. Restored full home page content in `index.html` (About, Research Interests, News).
2. Confirmed ICML 2026 paper was already listed under Conference Papers; updated title/authors/PDF/code links.
3. Added **Preprints** section to `publications.html` with four arXiv papers:
   - RUST-BENCH (`2511.04491`)
   - Reasoning Towards Fairness / ReGiFT (`2504.05632`)
   - Biased or Flawed (`2412.11414`)
   - Aligned at the Start (`2406.05315`)
4. Added `.preprint` venue-tag style in `_sass/pages/page.sass`.
5. Committed and pushed to `gh-pages` to redeploy GitHub Pages.

### Status
- Site live again; publications include Conference / Journal / Preprints.
