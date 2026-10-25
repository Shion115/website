# Publish updates to this portfolio

This is the existing `website` repository. Its public GitHub Pages URL is:

`https://shion115.github.io/website/`

## Option A — update files in the GitHub website

1. Sign in to GitHub as `Shion115` and open `https://github.com/Shion115/website`.
2. Select **Add file** → **Upload files**.
3. Upload the revised `index.html`, `README.md`, and `PUBLISHING.md` files from this folder. Keep the existing images and PDF files unchanged unless you intentionally want to replace them.
4. Enter a message such as `Refine NLP research portfolio`, then select **Commit changes**.
5. Wait a few minutes for GitHub Pages to rebuild, then open the public URL above.

## Option B — update with Git

From PowerShell, run:

```powershell
cd E:\Protfolio\website
git add index.html README.md PUBLISHING.md
git commit -m "Refine NLP research portfolio"
git push origin main
```

Then wait a few minutes and visit `https://shion115.github.io/website/`.

## Check before sharing

Open the site in a private/incognito browser window. Check the hero text, publication links, CV download, and both project links before sharing the URL.
