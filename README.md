# kawafriends.com

Pre-launch page for Kawa Friends, served by GitHub Pages from `main` (root).

- Standalone site: no shared Swiftian app menu, footer markup or cross-site links (founder 2026-11-11).
- DNS on Cloudflare, DNS only (never proxied), apex 4 A records to GitHub Pages (no AAAA, like seoulmal.com), `www` CNAME to `thinkswift.github.io`.
- Images: only the five friends' portraits, copied pixel for pixel from `KawaFriends/Sources/KawaFriends/Resources/portrait_*.png` (renders of the locked models, RDM-friends-3d-models-locked), cropped and scaled into `friends.png` and `og.png`; the page background is their background, #FBF4E7, light only. Founder asked for them 2026-11-11. No favicon yet.
- Visits: Cloudflare Web Analytics beacon (JS snippet, site created 2026-11-11). No App Store link yet; when one is added it needs `ct=web-kf-…` and the `appstore_click` sender (web-tags).
- Search Console: domain property `sc-domain:kawafriends.com` on the hello account; its TXT record lives on Cloudflare, never delete it.
- Registrar: Gabia. Nameservers: aiden / clara.ns.cloudflare.com.
