# obcchoir.fyi

Small unlisted site for the choir: a landing page plus three short links.

- `index.html`: the landing page with three buttons.
- `_redirects`: where `/attendance`, `/calendar` and `/music` point. To change a destination, edit its line and push.
- `_headers`, `robots.txt` and the `noindex` tag keep the site out of search engines.
- Hosted by a Cloudflare Worker that redeploys on every push to `main`.
- `.assetsignore` lists files that are not published (this README and config).
