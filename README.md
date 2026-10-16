# Phantom Ops

Static project page for the Phantom Ops research paper. The site is plain HTML
and CSS, with no build step or external dependencies, so GitHub Pages can serve
it directly from this repository.

## Publish with GitHub Pages

1. Push the repository to GitHub.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/(root)` folder, then save.

GitHub Pages will publish the site at the URL shown in the Pages settings.
Because `index.html` is at the repository root, no generator or workflow is
required.

## Customize

Edit `index.html` to replace the abstract, captions, and BibTeX placeholders.

- **Paper / Code links:** the buttons at the top of the page point to `paper.pdf` (add the PDF to the repo root) and `https://github.com/cam-cambridge/phantom-ops`. Update both `href`s (hero buttons and top nav) to the real locations.
- **Videos and images:** put files in [media/](media) and reference them with relative paths, e.g. `media/teleoperation-demo-01.mp4`. Use H.264 MP4 for broad browser support. GitHub rejects files over 100 MB, so compress large videos.
