# Handoff

**State** (2026-11-06): live at games.myjimmycloud.com from **Cloudflare Pages project `games`** (address `games-b3a.pages.dev`), a direct upload of `index.html` and the icons; the DNS record moved off GitHub Pages at 20:39 MT and answered 200 at 20:40. This branch takes out the `CNAME` file; it merges after a day (2026-11-07 or later), because until then GitHub Pages is the way back: one PATCH of the record to `jimmylowell.github.io`, DNS only. The README is merged.

**Next:** none for the site. **A merge goes live only by a deploy:** stage `index.html`, `favicon-32.png`, `favicon.ico`, `icon-192.png`, `icon-512.png` in a folder outside the repo and run `wrangler pages deploy <folder> --project-name games --branch main`. The Tools listing comes with the myjimmycloud.com front-page redo. A dated `Final` line goes here when Jimmy stamps it.

**Decided:** no `docs/design.md`; not worth one for a single page (finish lines, 2026-11-04). Cloudflare Pages over GitHub Pages for every myjimmycloud site (Jimmy, 2026-11-05).

**Open:** turning GitHub Pages off in the repo's Settings is Jimmy's, whenever; leaving it on costs nothing.
