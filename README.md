# kawafriends.com

Pre-launch page for Kawa Friends, served by GitHub Pages from `main` (root).

- Standalone site: no shared Swiftian app menu, footer markup or cross-site links (founder 2026-11-11).
- DNS on Cloudflare, DNS only (never proxied), apex 4 A records to GitHub Pages (no AAAA, like seoulmal.com), `www` CNAME to `thinkswift.github.io`.
- Images: only the five friends' portraits, copied pixel for pixel from `KawaFriends/Sources/KawaFriends/Resources/portrait_*.png` (renders of the locked models, RDM-friends-3d-models-locked), cropped and scaled into `friends.png` and `og.png`; the page background is their background, #FBF4E7, light only. Founder asked for them 2026-11-11. Favicon and the Mu tab/store icon: the red panda's face, close up (founder 2026-11-20: the old pixel panda did not look like our character; the whole Mu app icon made the face too small to read at favicon size, so the founder supplied this face crop, a 174 px image, sha256 3e72660ef48ec5a1…). It is a smooth illustration, not pixel art: sizes are Lanczos reductions, never `image-rendering: pixelated`. `favicon-32/64/128.png` and `assets/tabs/mu-32/64/128.png` (also on swiftian.com for the tabs) are the same files; favicon.ico holds those three PNG frames unchanged; apple-touch-icon = the face at 180.
- Visits: Cloudflare Web Analytics beacon (JS snippet, site created 2026-11-11). No App Store link yet; when one is added it needs `ct=web-kf-…` and the `appstore_click` sender (web-tags).
- Search Console: domain property `sc-domain:kawafriends.com` on the hello account; its TXT record lives on Cloudflare, never delete it.
- Registrar: Gabia. Nameservers: aiden / clara.ns.cloudflare.com.
- Privacy (`/privacy/`) and Help (`/support/`): the URLs the App Store listing gives (KawaFriends `fastlane/metadata/*/privacy_url.txt`, `support_url.txt`), written 2026-11-13 for the 1.0 listing; shared styles in `page.css`. Keep the privacy page in step with the app's `PrivacyInfo.xcprivacy` and the ASC privacy label.
