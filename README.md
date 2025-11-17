# MapOps Resource Hub

Single page internal hub for your MapOps tools, links, scripts, maps, prompts, and outbound assets.

This repo contains a single file:

- `index.html` – the entire dashboard (HTML, CSS, and JavaScript in one place)

## How to run locally

1. Download `index.html`.
2. Open it in your browser by double clicking the file.
3. Add your links on the right side form.
4. All resources are stored locally in your browser using `localStorage`.

## How to deploy to GitHub Pages

1. Create a new GitHub repository (for example `mapops-hub`).
2. Add `index.html` from this project to the root of the repo and commit it.
3. Go to **Settings > Pages** in the repo.
4. Under **Source**, choose:
   - Deploy from branch
   - Branch: `main`
   - Folder: `/ (root)`
5. Save. GitHub will build and give you a public URL like:

`https://your-username.github.io/mapops-hub/`

You can then bookmark that URL as your MapOps internal hub.

If you want to attach a custom domain later, you can:

1. Add a `CNAME` file in the repo with your desired domain.
2. Point your DNS records from your domain provider to GitHub Pages according to their docs.
