# Camp Mythos — Empire Points

Live points scoreboard for **Camp Mythos**, Culture & Identity Camp 2026 (15–17 Dec), Temasek Polytechnic.

- `index.html` — public scoreboard (view only, no account needed)
- `admin.html` — Game Master controls (organiser login required)
- `firebase-config.js` — Firebase project settings (public by design)
- `database.rules.json` — paste into Firebase → Realtime Database → Rules. Only the organiser emails listed there can change points.
