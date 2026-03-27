# GitHub Pages CV Site (Photo + PDF + Contact Form)

This package is ready to upload directly to a GitHub repository and publish with GitHub Pages.

## Included
- `index.html`
- `styles.css`
- `profile-placeholder.svg`
- `Puratchidasan_Munusami_CV.pdf`

## Notes
- The current photo is a placeholder. Replace `profile-placeholder.svg` with your own image and keep the same file name, or update the image path in `index.html`.
- The contact form currently uses `mailto:` so it opens the visitor's email app.
- If you want real form submission on GitHub Pages, connect the form to Formspree, Getform, or a serverless backend.

## Publish steps
1. Create a new GitHub repository.
2. Upload all files from this folder to the root of the repository.
3. Commit to the `main` branch.
4. In GitHub, open **Settings > Pages**.
5. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
6. Save.

Your website will be published at:
`https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPOSITORY_NAME/`
