# One Day. The Whole World. — Sunday 22 November 2026

Entry for the make.fun `news-image-20261122` bounty: sum up 22 November's
world news in one image.

- **Image:** `entry.png` — 1024×1024 PNG, 38 verified stories across 7 regions,
  dot-grid world map with numbered pins, enlarged Europe and Gulf insets,
  DATE CHECK box, consensus-leads strip.
- **Program:** `main.ts` (Node 22, standard library only) copies `entry.png`
  to `/output/entry.png` (or `$MAKEFUN_OUTPUT_DIR` outside the grader).
  Both graded runs produce byte-identical output.
- **Build tooling** (HTML front page + headless-Chromium screenshot driver)
  lives in `~/workspace/news-image-20261122/` and is not part of the entry.
