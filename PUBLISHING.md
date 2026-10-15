# Publishing this website on GitHub Pages

These instructions replace the files in the existing `tsaic2808/tsaic2808.github.io` repository while preserving the repository and its web address.

## Before uploading

1. Keep the original ZIP you downloaded from GitHub. It is your backup.
2. Extract the redesigned ZIP on your computer.
3. Open the extracted folder. Upload the **contents inside the folder**, not the outer folder itself.

## Upload the redesigned site

1. Sign in to GitHub and open `https://github.com/tsaic2808/tsaic2808.github.io`.
2. Select the **Code** tab.
3. Choose **Add file → Upload files**.
4. Drag all files and folders from inside the redesigned folder into the upload area.
5. At the bottom, enter the commit message `Launch modern portfolio redesign`.
6. Choose **Commit changes directly to the master branch**.
7. Select **Commit changes**.

GitHub's browser uploader replaces files with matching names, but it does not automatically delete old files that are absent from the new ZIP. Follow the cleanup list below after the new site is working.

## Confirm GitHub Pages settings

1. In the repository, open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Set the branch to **master** and the folder to **/(root)**.
4. Select **Save**.
5. Wait a few minutes, then visit `https://tsaic2808.github.io/`.

The **Actions** tab shows the deployment status. A green check mark means deployment succeeded.

## Remove old template pages

After the redesigned site is live, delete these old folders or files from GitHub if they remain:

- `_posts/`
- `_portfolio/`
- `_talks/`
- `_teaching/`
- `_drafts/`
- `_data/comments/`
- `markdown_generator/`
- `talkmap.py`
- `talkmap.ipynb`

Inside `_pages/`, retain only:

- `404.md`
- `about.md`
- `cv.md`
- `data-modeling.md`
- `home.md`
- `publications.md`
- `research.md`
- `sitemap.md`

To delete a file in GitHub: open it, select the three-dot menu, choose **Delete file**, and commit the change. Empty folders disappear automatically.

## If the update fails

1. Open the repository's **Actions** tab.
2. Select the failed Pages build.
3. Copy the red error message.
4. Send that message back in this chat; it will usually identify the exact file and line to fix.

Because your original ZIP remains unchanged, you can always restore the previous version by uploading its contents again.
