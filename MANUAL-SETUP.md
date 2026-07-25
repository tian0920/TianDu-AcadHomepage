# Manual GitHub Pages setup

This package is based directly on `RayeRen/acad-homepage.github.io`. The theme,
Jekyll layouts, Sass files, JavaScript, fonts, and workflow are preserved.
Personal information is stored in `_config.yml`, `_pages/about.md`,
`_pages/zh.md`, `_data/authors.yml`, and `_data/navigation.yml`.

## Publish

1. Sign in to GitHub and create a **public** repository named
   `YOUR_GITHUB_USERNAME.github.io`.
2. Extract this ZIP file. Upload **all** extracted files and folders to the
   repository root, including the hidden `.github` folder.
3. In `_config.yml`, replace:

   `YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME.github.io`

   with your real GitHub username and repository name.
4. Commit the files to the `main` branch. GitHub Pages will build the Jekyll
   site and publish it at `https://YOUR_GITHUB_USERNAME.github.io`.
5. To enable automatic Google Scholar citation updates, create a repository
   Actions secret:

   - Name: `GOOGLE_SCHOLAR_ID`
   - Value: `pJW7tXcAAAAJ`

6. Open the repository's **Actions** tab and enable workflows if GitHub asks.

## Optional replacements

- Replace `images/avatar.svg` with a real profile photograph, and update the
  `avatar` values in `_config.yml` and `_data/authors.yml`.
- Add a complete email address to `_config.yml` only if you want it shown
  publicly. The supplied Scholar record exposes only the verified domain, not
  the full address.
