# MycoWave

A kids' website for listening to mushroom signals, plus a simple mycologist viewer.
Made for the UQ Underground Brain project.

## Pages
- `index.html` — welcome screen ("Are you a kid or a mycologist?")
- `kids.html` — the kids' landing page
- `mycologist.html` — the mycologist observation viewer

## Put it on GitHub Pages
1. Create a new **public** repository on GitHub.
2. Click **uploading an existing file** and drag in everything in this folder
   (the three `.html` files, `README.md` and the `images` folder). Commit.
3. Go to **Settings → Pages**, set Source to **Deploy from a branch**,
   Branch to **main** and folder to **/ (root)**, then **Save**.
4. After 1–2 minutes the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Adding real mushroom sounds
1. Make an `audio/` folder and add files, e.g. `audio/pink-oyster.mp3`.
2. In `kids.html`, find the list of mushrooms near the bottom (`var M = [...]`)
   and fill in `audio: 'audio/pink-oyster.mp3'` for each one.
Clicking a mushroom will then play its recording.
