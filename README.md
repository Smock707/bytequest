# ByteQuest public pages

The public site: the landing page (`index.html`), `privacy.html`, `support.html`,
and `banned.json` (the arena ban list the app downloads).

It's published from the public repo Smock707/bytequest (GitHub Pages, `main` / root)
at **https://playbytequest.com** (domain registered at Porkbun, Nov 9, 2026).
The `CNAME` file sets the custom domain; keep it in the repo root.

- https://playbytequest.com/privacy.html  ← App Store Connect "Privacy Policy URL"
- https://playbytequest.com/support.html  ← App Store Connect "Support URL"
- https://playbytequest.com/banned.json   ← fetched by the app (`Moderation.listURL`, ColiseumService.swift)

The privacy and support URLs are also baked into the app (`AppLinks` in
JournalView.swift). Builds up to 48 carry the old
`smock707.github.io/bytequest/` URLs; GitHub Pages redirects those to the domain.

Contact email: hello@playbytequest.com (Porkbun email forwarding to Neal's Gmail).

DNS at Porkbun:
- `A` playbytequest.com → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- `CNAME` www → smock707.github.io
- MX and TXT records for email forwarding (added by Porkbun)
