# Packing Day: Willard Asylum

A small, contemplative, static website that invites visitors to pack six belongings for a fictional patient being admitted to Willard Asylum. Built with HTML/CSS/JS (no framework).

**Author:** Amy (Sparrow) Panton  
**Co‑creation:** with Claude (assistive scribing)  
**License:** See `LICENSE`

---

## Quick Deploy — GitHub Pages

1. Create a new GitHub repository, e.g. `packing-day-willard` (Public is fine).
2. Upload the contents of this folder (or push via git). Make sure `index.html` is at the repository root.
3. In your repo, go to **Settings → Pages**:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` (or `master`) — **folder:** `/ (root)`
   - Save. GitHub will build Pages and give you a live URL like: `https://<username>.github.io/packing-day-willard/`.

> Tip: If you're using a subfolder, ensure links are relative and test once live.

## Cite / Archive

- For permanence, archive a copy on **Zenodo** or **OSF** to mint a DOI.  
- Add that DOI link to the IJPT article footnote as the stable reference.

### Example citation

> Panton, Amy. *Packing Day: Willard Asylum* (website), 2025. GitHub Pages. DOI: _forthcoming_.

Add or edit `CITATION.cff` if you want automatic citation metadata in the repo.

## Accessibility (A11y) Checklist

- Semantic HTML: headings in order (`h1` → `h2`), lists for choices.
- Buttons/links have clear text; avoid “click here.”
- Keyboard navigation: ensure focus styles are visible; all interactive elements are reachable with `Tab`.
- Color contrast: verify text/background contrast meets WCAG AA (≥ 4.5:1).
- Alt text: all images (if any) have descriptive `alt` text. Decorative images use empty alt (`alt=""`).
- Motion sensitivity: avoid auto‑playing animations; keep interactions user‑initiated.
- ARIA: use landmarks (`<main>`, `<nav>`) if helpful; avoid over‑ARIA.

## Local Preview

Just open `index.html` in a browser. No build needed.

---

© 2025 Amy Panton
