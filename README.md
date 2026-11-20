# kawafriends.com

Pre-launch page for Kawa Friends, served by GitHub Pages from `main` (root).

- Standalone site: no shared Swiftian app menu, footer markup or cross-site links (founder 2026-11-11).
- DNS on Cloudflare, DNS only (never proxied), apex 4 A records to GitHub Pages (no AAAA, like seoulmal.com), `www` CNAME to `thinkswift.github.io`.
- Images: only the five friends' portraits, copied pixel for pixel from `KawaFriends/Sources/KawaFriends/Resources/portrait_*.png` (renders of the locked models, RDM-friends-3d-models-locked), cropped and scaled into `friends.png` and `og.png`; the page background is their background, #FBF4E7, light only. Founder asked for them 2026-11-11. Favicon: the red panda's face, close up, from the founder's 174 px crop (2026-11-20; it replaced the pixel panda, which did not look like our character). A smooth drawing, not pixel art: favicon-32/64/96.png are Lanczos reductions and the same files as swiftian.com `assets/tabs/cf-32/64/96.png` (the Math icon in the app menu); favicon.ico holds those three PNG frames; apple-touch-icon = the face at 180.
- Visits: Cloudflare Web Analytics beacon (JS snippet, site created 2026-11-11). No App Store link yet; when one is added it needs `ct=web-kf-…` and the `appstore_click` sender (web-tags).
- Search Console: domain property `sc-domain:kawafriends.com` on the hello account; its TXT record lives on Cloudflare, never delete it.
- Registrar: Gabia. Nameservers: aiden / clara.ns.cloudflare.com.
- Privacy (`/privacy/`) and Help (`/support/`): the URLs the App Store listing gives (KawaFriends `fastlane/metadata/*/privacy_url.txt`, `support_url.txt`), written 2026-11-13 for the 1.0 listing; shared styles in `page.css`. Keep the privacy page in step with the app's `PrivacyInfo.xcprivacy` and the ASC privacy label.
