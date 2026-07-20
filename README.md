# Afghan Flavour Website — GitHub Pages Upload Guide

This package contains the updated Afghan Flavour restaurant, bakery, catering, and complete priced menu website.

## Before uploading

1. Download the ZIP file provided by ChatGPT.
2. Right-click the ZIP and select **Extract All** on Windows, or double-click it on macOS.
3. Open the extracted folder. You should see `index.html`, `menu.html`, `catering.html`, other HTML pages, and an `assets` folder.
4. Upload the **contents inside this folder**, not the ZIP itself and not an extra outer folder.

## Upload to a new GitHub repository

1. Go to GitHub and sign in.
2. Click the **+** icon in the upper-right corner and select **New repository**.
3. Enter a repository name, such as `afghan-flavour-website`.
4. Choose **Public**. GitHub Pages on a standard account works most simply with a public repository.
5. Leave **Add a README**, `.gitignore`, and licence unchecked because this package already contains its own files.
6. Click **Create repository**.
7. On the repository page, click **uploading an existing file**. If that option is not visible, select **Add file → Upload files**.
8. In the extracted website folder, press `Ctrl+A` on Windows or `Command+A` on macOS to select all files and folders.
9. Drag them into the GitHub upload window. Confirm that GitHub shows `index.html`, `menu.html`, `catering.html`, and the `assets` folder at the repository root.
10. In **Commit changes**, enter a message such as `Upload updated Afghan Flavour website`.
11. Click **Commit changes**.

## Turn on GitHub Pages

1. Open the repository's **Settings** tab.
2. In the left sidebar, click **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Under **Branch**, choose `main` and choose `/(root)` for the folder.
5. Click **Save**.
6. Wait approximately 1–5 minutes.
7. Refresh the Pages settings screen. GitHub will show the website address, usually:
   `https://YOUR-USERNAME.github.io/afghan-flavour-website/`
8. Open the address and check Home, Menu, Catering, Bakery, Gallery, About, and Contact.

## Replace an older version already on GitHub

1. Open the existing repository.
2. Select **Add file → Upload files**.
3. Drag all files from this updated package into the upload window.
4. GitHub will show that existing files will be replaced and new files added.
5. Enter `Update menu and catering` as the commit message.
6. Click **Commit changes**.
7. GitHub Pages normally refreshes within 1–5 minutes. Use `Ctrl+F5` on Windows or `Command+Shift+R` on macOS if the old page is cached.

## Important folder structure

The repository root must look like this:

```
index.html
menu.html
catering.html
bakery.html
gallery.html
about.html
contact.html
.nojekyll
assets/
  styles.css
  site.js
  images/
```

Do not place all of these files inside another folder within the repository. `index.html` must be visible on the first repository screen.

## Custom domain

After the GitHub Pages site works, open **Settings → Pages → Custom domain**, enter `afghanflavour.ca`, and save. DNS records at the domain provider must also be updated before the custom domain will work.

## Updating prices later

Open `menu.html` directly on GitHub, click the pencil icon, change the relevant price, and click **Commit changes**. For larger changes, edit the local files and upload them again.
