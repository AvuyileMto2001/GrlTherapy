# HerCycle 🌸

HerCycle is a simple cycle-awareness and wellness journal website. It lets users save their cycle profile, view estimated cycle dates on a calendar, log daily moods/flow/symptoms/notes, review saved check-ins, and export or delete their local data.

## Project files
- `index.html` — HTML, plus the JavaScript functionality embedded in the page (no separate JS file).
- `style.css` — responsive styling.
- `README.md` — project documentation and deployment instructions.

## Run locally
1. Download or clone this repository.
2. Keep `index.html` and `style.css` together in the same folder.
3. Open `index.html` in a browser.

## Publish with GitHub Pages
1. Create a GitHub repository (or open the repository where you want this project).
2. Upload **both** `index.html` and `style.css` to the repository's root folder. Upload this README too.
3. On the repository, go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch **main** and folder **/(root)**, then press **Save**.
6. Wait a few minutes. GitHub will show the published website URL in the Pages section. Open that link to see your live site.

If you edit the files later, commit/push the updates to the selected branch and GitHub Pages will redeploy.

## Data and limitations
- HerCycle stores profile, journal entries, and reminder preferences in the current browser's `localStorage`. Data is not synced across browsers or devices and is not uploaded to a server.
- Export creates a JSON download; Delete all data removes the app's stored information from this browser.
- This static GitHub Pages version does not send scheduled email reminders.
- Cycle and fertile-window dates are estimates, not medical advice. Do not rely on them to confirm ovulation or prevent pregnancy.
- This is an educational wellness tool, not a medical device.
