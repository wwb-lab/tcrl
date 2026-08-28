# TCRL – Tribology & Corrosion Research Lab

Static website for the Tribology & Corrosion Research Lab at Oakland University. The site uses plain HTML, CSS, and JavaScript and requires no build step or package dependencies.

## Local preview

From this directory, run:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

## GitHub Pages deployment

The contents of this directory must be at the root of the GitHub repository so that `index.html` is in the repository root.

### Account or organization site

If the GitHub account or organization name `tcrl` is available, create the repository `tcrl.github.io` under that account and place these files in its root. The expected address is:

`https://tcrl.github.io/`

### Project site

Otherwise, create a repository named `tcrl` under your GitHub username and place these files in its root. The expected address is:

`https://YOUR-USERNAME.github.io/tcrl/`

For either option:

1. Push the site files to the repository's `main` branch.
2. Open **Settings → Pages** in the GitHub repository.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then save.
5. Wait for GitHub Pages to report that the site is live.

All site links and asset references are relative, so the same files work for both account and project sites.

## Development-only files

`tests/`, `REVIEW.md`, `.DS_Store`, Python cache files, local worktrees, and ZIP archives are not required by the published website. Keep them locally if useful, but do not include them in a clean deployment upload.

No remote repository or GitHub Pages deployment is created automatically by this project.
