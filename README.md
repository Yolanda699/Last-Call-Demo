# Last Call – online playtest table (Iteration 4)

A static website: 4 players, each on their own device, no accounts.
Art comes from the Last Call Figma file (exported to `img/`).

## Put it online with GitHub Pages (free, about 5 minutes)

1. On github.com, create a new **public** repository, e.g. `last-call-playtest`.
2. Click **Add file → Upload files** and drag in everything from this folder
   (`index.html`, `README.md` and the whole `img` folder). Commit.
3. Go to **Settings → Pages**. Under "Build and deployment", set **Source: Deploy from a branch**,
   **Branch: main**, folder **/ (root)**. Save.
4. After a minute the site is live at `https://<your-username>.github.io/last-call-playtest/`.

## How a session works

- One person opens the site, types their name and clicks **Open a new table**. That device *is* the table:
  keep that page open (and the screen awake) for the whole night.
- Everyone else opens the same link, types their name and the 4-letter code, and clicks **Join**.
- Everyone picks a role, then anyone clicks **Start the night**.
- If the host reloads, they type the same code and click **Join** to reopen the table (the game is saved on that device).
- Players connect browser-to-browser. The free PeerJS service (0.peerjs.com) only introduces the devices;
  no game data is stored online. Some strict school or office Wi-Fi networks block this kind of connection;
  if players can't join, try a phone hotspot.

## Updating rules or art

- Rules live in the `Last Call – Iteration 4 rules engine` section near the bottom of `index.html`
  (goal, timers, card effects, Night Events).
- Art lives in `img/` (WebP files exported from Figma). Replace a file with one of the same name to swap art.
