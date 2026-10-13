# Shengbao Wang — Academic Homepage

A lightweight, English-language academic homepage for **Shengbao Wang**, Hangzhou Normal University.

## Site map

- `index.html` — academic homepage, with three prominent research links
- `dh-protocols.html` — On DH Protocols
- `ibe.html` — Identity-Based Encryption
- `dijkstra.html` — Dijkstra and Shortest Paths, with the English v14 manuscript PDF
- `assets/style.css` — responsive site styling (no external dependencies)
- `assets/dijkstra-global-to-local-v14.pdf` — embedded manuscript

## Publish on GitHub Pages

1. Create a **public** repository named `PaulWang2024.github.io` (matching your GitHub username, case-insensitively).
2. **Extract** the ZIP archive and upload its *contents* to the **root** of the repository. Do not upload the ZIP by itself and do not nest the files in a folder.
3. In the repository, choose **Settings → Pages → Build and deployment**:
   - **Source**: Deploy from a branch
   - **Branch**: `main`
   - **Folder**: `/(root)`
4. Save the settings. Once deployment is complete, the site should be available at `https://paulwang2024.github.io/`.
5. To help visitors reach the site from your GitHub profile, set the **Website** field at `https://github.com/settings/profile` to `https://paulwang2024.github.io/`.

## Editing

- Update your biography and research links in `index.html`.
- Replace generic research-topic text in `dh-protocols.html` or `ibe.html` with verified article titles and URLs as desired.
- Replace the v14 PDF in `assets/` as the Dijkstra manuscript evolves, or update the link in `dijkstra.html` to point to the dedicated project page.

All pages are static HTML + CSS and can be used without a build system, JavaScript, or external font services.
