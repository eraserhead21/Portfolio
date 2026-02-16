# GitHub Pages Portfolio (Jekyll + Minimal Mistakes)

## What this is
A clean technical-writing portfolio site using the **Minimal Mistakes** Jekyll theme and a top navigation bar.

## Quick setup
1. Create a GitHub repo:
   - **User site (recommended):** `YOUR_GITHUB_USERNAME.github.io`
   - **Project site:** `portfolio` (or any name)

2. Upload all files from this folder to the repo root.

3. Edit `_config.yml`:
   - Set `url: "https://YOUR_GITHUB_USERNAME.github.io"`
   - Set `baseurl`:
     - User site: `""`
     - Project site: `"/REPO_NAME"` (example: `"/portfolio"`)
   - Update `title` and `description`

4. Turn on GitHub Pages:
   - Repo → **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: `main`
   - Folder: `/ (root)`

## Add your work
- Case studies live in `_case_studies/`
- Samples live in `_samples/`
- PDFs/images live in `assets/`

## Notes
- If you see build errors, check the Actions/Pages build logs.
- Minimal Mistakes docs: https://mmistakes.github.io/minimal-mistakes/
