# Log

Append-only record of all operations.

---

- **2026-11-07** — Setup: created `CLAUDE.md`, `raw/`, `processed/`, `notes/index.md`, `notes/log.md`, and empty `raw/New_Notes.md`. No raw notes found to process.
- **2026-11-07**: Ingested `raw/New_Notes.md` (3 notes) and moved it to `processed/New_Notes_2026-11-07.md`.
  - Added the Earth embeddings article to `Remote_Sensing.md` (new page) and linked it from `Embeddings.md` (new page).
  - Added agribound to `Agriculture.md` (new page) and linked it from `Remote_Sensing.md`, `Embeddings.md` and `Python.md` (new page).
  - Added the Groundsource flood dataset to `Climate_Change.md` (new page) and linked it from `Data.md` (new page).
  - Updated `index.md` with all 6 pages.
- **2026-11-07**: Website setup from the personal-notes-website-template.
  - Added `mkdocs.yml` (nav set to the 6 current pages), `hooks.py` (changed so back-links aren't counted as notes and files are read as UTF-8), `requirements.txt`, `.github/workflows/deploy.yml` and `.gitignore`.
  - Added "Latest Finds" to `index.md` and moved the page tables under "Topics".
  - Added an "Update the Website" section to `CLAUDE.md`.
- **2026-11-07**: Published the site. Created the public repo `danmulat/personal-notes`, pushed, and turned on GitHub Pages (source: GitHub Actions). The site is live at https://danmulat.github.io/personal-notes/. Added `.obsidian/workspace.json` to `.gitignore`.
- **2026-11-07**: Ingested `raw/New_Notes.md` (1 note) and moved it to `processed/New_Notes_2026-11-07_2.md`.
  - Added "PostGIS spatial joins, translated to DuckDB" (Geomermaids) to `SQL.md` (new page).
  - Added SQL to `index.md` (Topics and Latest Finds) and to the `mkdocs.yml` nav.
