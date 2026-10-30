# GOFOR — BMVC 2026 project website

This is an independent GitHub Pages project page for:

**Gradient-Free Orthogonal Feature Organization for Online Task-Free Class-Incremental Learning**  
Parinita Nema and Vinod K. Kurmi — Accepted at BMVC 2026.

## Publish under your personal GitHub account

The existing WACV 2025 page under `VisDomLab/FeatAugFSCIL` was used as a visual reference only. This site uses the BMVC/GOFOR paper content, not the WACV/FACL content.

### Option A: Separate project repository (recommended)

1. Log in as `Parinitanema` (your public research GitHub account) or the personal username you wish to use. **The ChatGPT GitHub connection was to `nemaparinita160-spec`, a different username**, so select the correct account in GitHub before publishing.
2. Create a new **public** repository named `GOFOR-BMVC2026`; do not initialize it with a README.
3. Extract this ZIP, then from inside the extracted `GOFOR-BMVC2026` directory run:

   ```bash
   git init
   git add .
   git commit -m "Publish GOFOR BMVC 2026 project website"
   git branch -M main
   git remote add origin https://github.com/Parinitanema/GOFOR-BMVC2026.git
   git push -u origin main
   ```

   If your GitHub account is not `Parinitanema`, replace that name in the remote URL.
4. On the repository, select **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
5. The resulting page address will be `https://parinitanema.github.io/GOFOR-BMVC2026/` when using the `Parinitanema` account. Other usernames produce a corresponding URL.

### Option B: Add to an existing personal website

If you maintain `Parinitanema/Parinitanema.github.io`, copy this entire directory as `GOFOR-BMVC2026/` inside that repository's publishing source. Your website will be at `https://parinitanema.github.io/GOFOR-BMVC2026/`. This does not need a separate repository or new GitHub Pages configuration if the site is already publishing from that source.

## Site files

- `index.html`: all page styling and content (fully editable, no build system).
- `assets/gofor_framework.jpg`: original GOFOR method figure extracted from the author-provided PDF.
- `assets/paper_preview.webp`: paper cover preview.
- `assets/GOFOR_BMVC2026.pdf`: copy of the available BMVC manuscript; replace with the final published version when appropriate.
- `.nojekyll`: disables unnecessary Jekyll processing.

## Before public release

- Verify that the PDF is the exact version you wish to make public.
- Add the genuine GOFOR code repository URL when available; the code card deliberately has no fake link.
- Update the BibTeX record with the final publisher/proceedings citation once released.
- The paper website is independent of VisDomLab, with no VisDom logo or branding.
