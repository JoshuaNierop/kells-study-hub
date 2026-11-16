# Study Hub — To Do

## Hosting

- [ ] P1 — Migratie van GitHub Pages naar Cloudflare Pages. Workspace-default is nu Cloudflare. Cloudflare Pages koppelen aan `JoshuaNierop/kells-study-hub`, build output leeg (static), GitHub Pages daarna uitzetten.

## Backlog

- [ ] P2 — Planning.md en Readme.md aanmaken in Metadocs

## Code-audit 2026-11-17
- [x] P3 — Code-audit uitgevoerd: ongebruikte + onnodig complexe code (2026-11-17)
- [x] P2 — Verwijderd: ongebruikte CSS (digest-*, empty-state, tab-icon, tab-add; index.html, ~97 regels)
- [ ] P2 — index.html is 4900 regels met CSS, content en JS in één bestand: splitsen naar css/ en js/ bestanden (statische site, geen build nodig) — gemiddeld risico, geen tests
- [ ] P3 — Review: `.vb-label` (index.html:~830) en `.mech-arrow-split` (Infographic/infographic.html:298) lijken ongebruikt; niet verwijderd
- [ ] P3 — Review: 11 identieke regels op index.html:107-117 en :1345-1355 — mogelijk CSS vs. JS-string, niet onderzocht
