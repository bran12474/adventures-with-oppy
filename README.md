# Adventures with Oppy: project website

One page, no build step. It runs on GitHub Pages for free.

## 1. Put it online (about 10 minutes)

1. On github.com, click **New repository**. Name it something like `adventures-with-oppy`, set it to **Public**, and click **Create repository**.
2. On the new repo page, click **uploading an existing file**. Drag in `index.html`, `README.md`, and the whole `assets` folder (keep the folder structure). Click **Commit changes**.
3. Go to **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, then click **Save**.
4. Wait a minute or two. Your site will be at:
   `https://YOUR-USERNAME.github.io/adventures-with-oppy/`
5. Whenever you upload a changed file, the site updates within a minute or so.

## 2. Fill in your content

**Links.** Open `index.html` and search for `SETTINGS` (near the bottom). Paste these between the quotes:
- `video`: your 30-second video (a YouTube, Vimeo, or Google Drive link)
- `play`: where judges can play or download the game
- `code` and `project` (optional): your code repo and your Space Apps project page

Buttons for any link you leave empty stay hidden.

**Placeholders.** Search `index.html` for `class="fill"`. Replace each whole `<span class="fill">[...]</span>` with your own text, such as your team name, roles, game engine, and CAD software.

**Images and videos.** Drop files into `assets/`, using the names in `assets/README.txt`, all lowercase. CAD renders can be `.png`, `.jpg`, `.gif`, or a turntable `.mp4`. The page finds them on its own. Until it does, it shows a labeled placeholder box.

**Optional 3D models.** If you add `assets/models/<part>.glb` (for example `pancam.glb`), that part's card gets a **Spin in 3D** button. Onshape can export glTF directly. From Fusion 360 or SolidWorks, export STL or OBJ, then open it in Blender (File → Import) and use File → Export → glTF 2.0 (.glb).

**See what's left.** Open your site with `?edit` at the end of the address, e.g. `https://YOUR-USERNAME.github.io/adventures-with-oppy/?edit`. A checklist lists every missing file and placeholder.

GitHub's web uploader limits each file to 25 MB. If your trailer is bigger, put it on YouTube and paste the link instead.

## 3. Space Apps rule reminders

- **AI disclosure.** Teams must say where and how they used AI. This site was built with help from Claude (Anthropic): it wrote the page code, drafted the text from the listed NASA sources, and drew the diagrams labeled "AI-generated illustration." Say this in your submission's AI-use field. Keep the footer note and the labels. If you replace a diagram with your own image, that image doesn't need a label.
- **No NASA branding.** Don't add NASA logos, flags, or mission patches to the site or game media.
- **Demo video.** Up to 30 seconds, with English subtitles, hosted on a public link.
- **Public link.** The project link must open without a password, permission, or sign-in. GitHub Pages does that.

Before you submit, click every link in the Sources section once to make sure it opens.
