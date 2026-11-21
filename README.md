# David Rydell, 1963 – 2026

A simple tribute page with the details of David's funeral service and reception.
It is a plain static site (`index.html`, one photo and a calendar file), so it can be
hosted free on GitHub Pages.

## Publishing on GitHub Pages

1. Create a new public repository on GitHub (for example `david-rydell`).
2. Push this folder to it:

   ```bash
   git remote add origin https://github.com/<your-username>/david-rydell.git
   git push -u origin main
   ```

3. On GitHub, open the repository's **Settings → Pages**, set **Source** to
   *Deploy from a branch*, choose `main` and `/ (root)`, and save.
4. After a minute the page will be live at
   `https://<your-username>.github.io/david-rydell/`.

## Editing

All the text is in `index.html`. To change the photo, replace `images/david.jpg`.
