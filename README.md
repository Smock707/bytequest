# ByteQuest public pages

`privacy.html` + `support.html` — the two URLs baked into the app (`AppLinks` in
`JournalView.swift`) and required by App Store Connect.

To publish (once):

1. Create a **public** GitHub repo named `bytequest` under the `nealfc` account.
2. Push these three files to the repo root (`main` branch).
3. Repo Settings → Pages → Source: **Deploy from a branch** → `main` / `/ (root)` → Save.
4. Verify both URLs load:
   - https://smock707.github.io/bytequest/privacy.html  ← App Store Connect "Privacy Policy URL"
   - https://smock707.github.io/bytequest/support.html  ← App Store Connect "Support URL"

Published under Smock707 on Aug 28, 2026. If the repo name or account ever changes, update the two constants in `AppLinks`
(JournalView.swift) to match before archiving.
