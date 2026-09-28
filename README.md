# Stride Journal

A walk and run tracker with a 12-week walking plan, a daily calorie target, and progress toward a goal weight. Runs entirely in the phone's browser. Data is saved on the phone, with a backup/restore option.

## Put it online (GitHub Pages)

1. Create a new **public** repository on GitHub, for example `stride-journal`.
2. Click **uploading an existing file** and drag in everything from this folder: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md`, and the `icons` folder. Commit.
3. Go to **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**. Save.
4. After a minute or two, the site is live at `https://YOUR-USERNAME.github.io/stride-journal/`.

## Put it on her phone

- **iPhone:** open the link in **Safari**, tap Share, then **Add to Home Screen**. From then on, always open it from the home-screen icon. The icon keeps its own data, separate from Safari.
- **Android:** open the link in **Chrome**, tap ⋮, then **Add to Home screen** or **Install app**.

## Updating the app later

Upload the changed files to the repo. In `sw.js`, change `stride-v1` to `stride-v2` (and so on) so phones pick up the new version. The update shows up the second time she opens the app.

## Notes

- Nothing she enters is sent anywhere. It stays on her phone.
- Use **History → Save backup** every few weeks. On iPhone, save the file to iCloud Drive or Files.
- GPS distance works while the app is open with the screen on. If the phone locks mid-walk, distance can come up short.
