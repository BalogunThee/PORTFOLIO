# Portfolio — GitHub Pages Instructions

This folder contains a ready-to-host static portfolio site.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Main portfolio page |
| `Index css.css` | Styling for the page (must stay in the same folder as `index.html`) |
| `profile.png` | Portrait photo used in the hero section |

## How to upload to GitHub

1. **Create a new repository** on GitHub (e.g., `portfolio`).
2. **Upload the three files** (`index.html`, `styles.css`, `profile.png`) to the **root** of the repository.
3. Do **not** rename the files. GitHub is case-sensitive, so `styles.css` must stay exactly `styles.css`.
4. Commit the files.

## How to enable GitHub Pages

1. Go to your repository on GitHub.
2. Click **Settings** → **Pages** (in the left sidebar).
3. Under **Source**, select **Deploy from a branch**.
4. Select the **`main` branch** and the **root** folder, then click **Save**.
5. Wait 1–2 minutes. Your site will appear at:

   ```
   https://<your-username>.github.io/<repository-name>/
   ```

## Important notes

- The CSS link inside `index.html` is: `<link rel="stylesheet" href="Index css.css">`. This only works if `Index css.css` is in the same folder as `index.html`.
- If you put the files in a subfolder (e.g., `portfolio/`), the link will break. Keep them in the repository root.
- If you do not see the styles, press `Ctrl + Shift + R` (or `Cmd + Shift + R` on Mac) to hard-refresh the page, or clear your browser cache.

## Quick check after uploading

Open the live site and inspect the page. If it looks plain (no dark background, no styled cards), it usually means the CSS file is missing or misnamed. Go back to your repository and confirm that `Index css.css` exists and is spelled exactly like that.
