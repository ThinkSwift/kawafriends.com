# kawafriends.com

Pre-launch page for Kawa Friends, served by GitHub Pages from `main` (root).

- Standalone site: no shared Swiftian app menu, footer markup or cross-site links (founder 2026-11-11).
- DNS on Cloudflare, DNS only (never proxied), apex 4 A records to GitHub Pages (no AAAA, like seoulmal.com), `www` CNAME to `thinkswift.github.io`.
- Images: only the five friends' portraits, copied pixel for pixel from `KawaFriends/Sources/KawaFriends/Resources/portrait_*.png` (renders of the locked models, RDM-friends-3d-models-locked), cropped and scaled into `friends.png` and `og.png`; the page background is their background, #FBF4E7, light only. Founder asked for them 2026-11-11. Favicon and the Mu tab/store icon: the Mu app icon itself (the red panda with the question mark), founder 2026-11-20 — the old pixel panda left the web because it did not look like our character. `favicon-32/64/128.png` and `assets/tabs/mu-32/64/128.png` (also on swiftian.com for the tabs) are byte-identical copies of MultiplicationTimesTables `AppIcon.appiconset/32.png`, `64.png`, `128.png`; favicon.ico holds those three PNG frames unchanged; apple-touch-icon = the iOS 1024 app icon at 180, as iOS draws it on the home screen.
- Visits: Cloudflare Web Analytics beacon (JS snippet, site created 2026-11-11). No App Store link yet; when one is added it needs `ct=web-kf-…` and the `appstore_click` sender (web-tags).
- Search Console: domain property `sc-domain:kawafriends.com` on the hello account; its TXT record lives on Cloudflare, never delete it.
- Registrar: Gabia. Nameservers: aiden / clara.ns.cloudflare.com.
- Privacy (`/privacy/`) and Help (`/support/`): the URLs the App Store listing gives (KawaFriends `fastlane/metadata/*/privacy_url.txt`, `support_url.txt`), written 2026-11-13 for the 1.0 listing; shared styles in `page.css`. Keep the privacy page in step with the app's `PrivacyInfo.xcprivacy` and the ASC privacy label.
