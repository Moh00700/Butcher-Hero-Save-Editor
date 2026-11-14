# 🎮 Butcher Hero Save Editor

Edit your Butcher Hero `game_data.bin` save file — right in your browser.

**Use the editor here 👉 [Site Link](https://moh00700.github.io/Butcher-Hero-Save-Editor/)**

> ⚠️ If that link gives a 404, your repo name is slightly different. Check the exact name on your repo's **Code** tab — the link must match it exactly, including capitals and dashes: `https://moh00700.github.io/<your-exact-repo-name>/`

## 📖 How to use

**1. 📂 Find your save file (Android)**
- Open your file manager and go to **Internal storage > Android > data**
- Find the **Butcher Hero** folder > **files** > `game_data.bin`
- On Android 11 and later that folder is often blocked for normal file managers — if you cannot see it, use a file manager with Shizuku / ADB access, or a PC file transfer.
- If you still cannot see it, the file lives in the game's private app storage (`/data/data/…`), which needs root or ADB access to reach.

**2. 💾 Back up your save**
- Copy the original `game_data.bin` somewhere safe before editing. If anything goes wrong, you can put the backup back.

**3. ✏️ Edit**
- Open the editor link above and tap **Open your game_data.bin**, then pick your file.
- Change any value in the tabs: Player Stats, Weapons, Shields, Helmets, Accessories, Gems and Souls, Vip Privileges, Crystal Event, Crystal System, Boss Tower, Blacksmith Sharpening, Level Pass, Passes and Offers.
- **➕ Add missing items:** each gear tab (Weapons, Shields, Helmets, Accessories) has an **Add missing** button that lists exactly which items are missing in that tab and queues them to be added when you save. Items you already own are never touched.

**4. ✅ Save and put it back**
- Tap **Save game_data.bin**.
- Close the game completely, then put the edited file back in the **same place with the exact same name**.

## 🔒 Privacy

Everything runs in this page. Your save file is never uploaded anywhere — it is read and edited on your own device. The integrity hash is recalculated for you on save.

## 🔄 Updating this site

This repo is a GitHub Pages site. To update the editor, replace `index.html` in the repo root with the new version (keep `README.md` and `.nojekyll` where they are). Pages redeploys automatically in about a minute.
