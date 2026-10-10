# mc.girard-davila.net

Public documentation site for our home **Minecraft Java** server (Paper 26.2):
config, plugin list, worlds, maps/screenshots, and an agenda of future LAN parties.

- **Site:** https://mc.girard-davila.net (GitHub Pages)
- **Hugo** (extended) — French first, English later (i18n)
- **Hero form:** Formspree (register interest for future LAN parties)

## Local dev

```bash
hugo server -D
```

## Content layout

- `content/*.fr.md` — French (default)
- `content/*.en.md` — English (secondary)
- `data/plugins.yml` — plugin inventory (kept in sync by `bin/mc-site-export`)
- `data/events.yml` — LAN-party agenda (next parties TBA)
- `data/worlds.yml` — gallery entries
- `static/images/{maps,screens}` — map renders and in-game screenshots

## Formspree

Forms are defined in `formspree.json` and deployed with the Formspree CLI:

```bash
FORMSPREE_DEPLOY_KEY=... npx @formspree/cli deploy
```

The public endpoint id (`https://formspree.io/f/<hash>`) goes in `hugo.yaml`
(`params.formspree_id`). The **deploy key is a secret** and must never be committed.

## Deploy

Push to `main` → GitHub Actions builds Hugo and publishes to GitHub Pages.

## Notes

- The Minecraft server is **LAN-only for now**; the public address is TBA.
- Server first light: **2026-10-10**.
