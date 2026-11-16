# All-Star Team-Up 2K Arena

Private 5v5 NBA 2K tournaments on PS5, PS4, Xbox Series X|S and Xbox One. Build a squad of real All-Stars, win your group, then fight through a double-elimination bracket. $50/team or $15 solo. $450 prize pool per event. Support: eufraciomart26@gmail.com

Two files make the site: `index.html` (the whole website) and `data.json` (teams, brackets, scores, settings).

## Publish on GitHub Pages
1. Create a free GitHub account and sign in.
2. Click **+** (top right) > **New repository**. Name it, set it to **Public**, tap **Create repository**.
3. On the empty repo page, tap **uploading an existing file**. Drag in `index.html` and `data.json` (not a zip).
4. Tap **Commit changes**.
5. Open **Settings** > **Pages**. Under Build and deployment, set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, then **Save**.
6. Wait 1 to 2 minutes and refresh. GitHub shows your public link: `https://YOUR-USERNAME.github.io/REPO-NAME/`

## Edit the site (admin)
1. Open your site with `#admin` on the end, for example `https://YOUR-USERNAME.github.io/REPO-NAME/#admin`.
2. First time: set a passphrase (8+ characters).
3. Edit teams, groups, brackets and scores. Changes stay as a draft in your browser.
4. Tap **Download data.json**.
5. In GitHub open your repo, tap **Add file** > **Upload files**, drop in the new `data.json` (same name), tap **Commit changes**.
6. Wait about a minute. Everyone sees the update after a refresh.

Keep editing from the same browser until you have uploaded, since drafts are stored there.

## Security note
The admin passphrase only locks the editing screen in your browser. What visitors see is whatever `data.json` is in your repo, and only people with write access to your repo can change that. Use a strong GitHub password and turn on two-step login.
