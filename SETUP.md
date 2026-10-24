# Setup your pastel cookie profile

## 1. Create the profile repository

Create a **public** GitHub repository named exactly `lyri3aly` (or replace that with your own GitHub username). GitHub displays its `README.md` on your profile.

## 2. Upload these files

Upload everything in this folder to the root of that repository. Keep the `assets/` and `game/` folders in place.

## 3. Enable GitHub Pages

In the repository, open **Settings → Pages**. Under the build/deployment settings, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. Wait for GitHub Pages to publish.

The game URL should be `https://YOUR-USERNAME.github.io/YOUR-USERNAME/game/`. The README currently links to `https://lyri3aly.github.io/lyri3aly/game/`; change that link if your username or repository name differs.

## 4. Personalize the README

Edit the intro, quest log, project descriptions, and technology icons so they accurately represent you. The Rhythm Crossing repository link is prefilled. Add your actual Inkless repository URL before publishing that project card.

## 5. Test the game

Open `game/index.html` locally to test the cookie clicker. It has click counting, upgrade costs, cookies-per-second production, local save progress, and limited offline earnings. GitHub Pages is needed for the README's hosted game link to work publicly.

## Notes

- GitHub READMEs cannot execute JavaScript, so the cookie image links out to the separate game page.
- Progress is stored in that browser's local storage; it does not sync between devices.
- The README uses externally hosted Shields.io and Skill Icons images. The game itself has no external JavaScript dependencies.
