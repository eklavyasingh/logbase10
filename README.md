# logbase10 website

A single static page — `index.html` — with all CSS and JS inline. No build step, no dependencies to install.

## Hosting on GitHub Pages

1. Create a new repository on GitHub (e.g. `logbase10-site`).
2. Add `index.html` to the root of that repository (via the web UI's "Add file → Upload files", or by cloning locally and committing it).
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Set **Branch** to `main` (or `master`) and folder to `/ (root)`, then **Save**.
6. GitHub will give you a live URL, usually:
   `https://<your-username>.github.io/<repo-name>/`
   It can take a minute or two to go live after the first save.

## Using a custom domain (optional)

If you buy a domain later:
1. In **Settings → Pages**, enter it under **Custom domain**.
2. Add a `CNAME` record at your domain registrar pointing to `<your-username>.github.io`.
3. GitHub will auto-generate a `CNAME` file in your repo — leave it there.

## Making changes later

Just edit `index.html` directly (it's plain HTML/CSS/JS — searchable by section comments and class names) and commit. GitHub Pages redeploys automatically on every push to the branch you selected.
