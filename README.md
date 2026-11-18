# Your academic website

## What's in this folder

| File | What it is |
|---|---|
| `index.html` | The website itself. You never need to edit this. |
| `data.js` | **All your content** — name, education, publications, everything. |
| `editor.html` | A form editor with live preview for changing `data.js`. |
| `images/` | Put your photos here (profile picture, gallery, etc.). |

## Editing your content

1. Open `editor.html` in Chrome or Edge. (Double-clicking it works. If the preview stays blank, see the note at the bottom.)
2. Pick a tab on the left (Profile card, Education, Publications…) and type. The preview on the right updates as you go.
   - **Add / Delete / ↑ ↓** buttons add items, remove them, and reorder them.
   - **Sections & order** turns whole sections on or off and changes their order in the menu.
   - **Site settings → Colour theme** switches between teal, blue, purple, maroon and amber.
3. Click **Download data.js** and replace the old `data.js` in this folder with the new one.

Your work is saved in the browser as you type, so closing the editor won't lose it. **Discard draft** goes back to what's in `data.js`.

**Photos:** the Upload button embeds a resized copy of the photo in `data.js`, which is fine for your profile picture and a few references. For a gallery of many photos, copy them into `images/` and type the path instead, e.g. `images/lab1.jpg`.

**CV:** copy your CV PDF into this folder and type its file name (e.g. `Mouri_CV.pdf`) into Profile card → CV file. A "Download CV" button appears.

Placeholders to replace are shown in `[square brackets]`.

## Putting it online with GitHub Pages (free)

1. Create a GitHub account. Your site address will be `https://YOUR-USERNAME.github.io`.
2. Make a new **public** repository named exactly `YOUR-USERNAME.github.io`.
3. In the repository, click **Add file → Upload files**, and drag in everything from this folder (`index.html`, `data.js`, `editor.html`, `images/`, your CV). Click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
5. After a minute or two the site is live at `https://YOUR-USERNAME.github.io`.

**To update later:** edit with `editor.html` (you can even use the online copy at `https://YOUR-USERNAME.github.io/editor.html`), download the new `data.js`, and upload it to the repository again (Add file → Upload files → it replaces the old one).

If you'd rather keep the editor private, don't upload `editor.html` — just keep it on your computer next to `data.js`.

## Note on the live preview

Some browsers restrict local files. If the editor's preview stays blank when opened by double-click, either use Chrome/Edge, or use the online copy after uploading to GitHub. The site itself (`index.html`) always works.
