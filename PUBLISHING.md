# Publish this NLP research portfolio as a separate GitHub Pages site

The proposed repository name is `tasfia-nlp-research`. With the `Shion115` GitHub account, the final public URL will be:

`https://shion115.github.io/tasfia-nlp-research/`

## Option A — upload in the GitHub website

1. Sign in to GitHub as `Shion115`.
2. Select the **+** button in the upper-right corner, then choose **New repository**.
3. Set the repository name to `tasfia-nlp-research` and choose **Public**.
4. Do **not** select “Add a README file”, “Add .gitignore”, or “Choose a license”. This folder already has the files it needs.
5. Select **Create repository**.
6. On the empty repository page, select **uploading an existing file**.
7. Open `E:\Protfolio-nlp-research` in File Explorer. Select and upload these files:
   - `.gitignore`
   - `index.html`
   - `README.md`
   - `Tasfia_Jannat_Tasfi_CV.pdf`
   - `Tasfia_Jannat_Tasfi.pdf`
   - `IMG_20260121_223602.png`
   - `Huawei.jpg`
   - `Hult_prize.jpeg`
   - `Waymakers.jpeg`
   - `PUBLISHING.md` (optional; it does not affect the site)
8. Enter a commit message such as `Publish NLP research portfolio`, then select **Commit changes**.
9. Open the repository **Settings**, then select **Pages** in the left sidebar.
10. Under **Build and deployment**, choose **Deploy from a branch**.
11. Set the branch to `main`, set the folder to `/ (root)`, and select **Save**.
12. Wait a few minutes, refresh the Pages settings screen, and open the published URL shown there.

## Option B — publish with Git commands

After creating the empty public repository in steps 1–5 above, open PowerShell and run the following commands. Replace `YOUR_GITHUB_USERNAME` only if the account is not `Shion115`.

```powershell
cd E:\Protfolio-nlp-research
git init -b main
git add .
git commit -m "Publish NLP research portfolio"
git remote add origin https://github.com/Shion115/tasfia-nlp-research.git
git push -u origin main
```

Then complete steps 9–12 above to turn on GitHub Pages.

## Before emailing

Open the final URL in an incognito/private browser window. Check the portrait, CV download, project links, email button, and mobile layout. Use this new URL in the email; your existing `portfolio` site remains unchanged.
