# MapOps Resource Hub (Links + Files)

This version of the MapOps Hub lets you save:

- Name
- Category
- Optional URL
- Optional file from your laptop (PDFs, small decks, etc.)

Each card can be:

- Link only
- File only
- Link + file

Everything is stored locally in your browser using `localStorage`, including the file contents (as data URLs). This is a convenience hub, not cloud backup, so keep attached files reasonably small and important.

## How to use

1. Open `index.html` in your browser.
2. Use the form on the right:
   - Name (required)
   - URL or path (optional)
   - Category
   - Attach file (optional)
3. Click **Add to hub**.
4. In the cards list:
   - **Open link** opens the URL in a new tab
   - **Open file** downloads or opens the attached file

## GitHub Pages

1. Create a repo (for example `mapops-hub`).
2. Add `index.html` to the root and commit.
3. Settings → Pages → Source: Deploy from branch → `main` → `/ (root)`.
4. Save. GitHub will give you a public URL for your hub.
