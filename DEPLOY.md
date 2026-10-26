# Publishing the RRI Texture Wiki

This folder is a standalone **Docsify + GitHub Pages** site. It does not require Node, npm, or a build step.

1. Create a normal GitHub repository (or use a dedicated documentation repository).
2. Upload **all files and folders in this directory** to the repository root, including `.nojekyll` and `texture-guide-assets`.
3. Open **Settings → Pages → Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`.
4. Wait for GitHub Pages to publish the site.
5. Edit the Markdown files in GitHub to update the content. Refresh the site to see changes.

**Important:** A GitHub Wiki (`repository.wiki.git`) is different from a normal GitHub Pages repository. Upload the `github-wiki` folder contents to the Wiki repository, or the `github-pages` folder contents to a regular repository. Do not put the Pages HTML in the GitHub Wiki expecting GitHub to run it.

To preview locally, run `python -m http.server 3000` from this folder and open `http://localhost:3000`.

The tutorial screenshots are included locally. Existing GitHub-hosted screenshot links in the 2D/3D guides have been preserved.
