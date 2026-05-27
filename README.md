# kombuese-privacy

Quellrepo für die öffentlich gehosteten **Datenschutz-** und **Support-Seiten** der iOS-App **Kombüse**.

## Veröffentlichte URLs

| Zweck | URL |
|---|---|
| Datenschutzerklärung | https://nils3311.github.io/kombuese-privacy/ |
| Support / FAQ | https://nils3311.github.io/kombuese-privacy/support/ |

Beide URLs werden im App-Store-Connect-Submit als „Privacy Policy URL" und „Support URL" eingetragen.

## Struktur

- `index.md` — Datenschutzerklärung (DE + EN)
- `support.md` — Support-Seite mit FAQ + Kontakt (DE + EN)
- `_layouts/default.html` — gemeinsames Layout, Brand-Tokens (Waldgrün/Tomate/Sand), Fraunces + Inter via Google Fonts, Dark Mode
- `_config.yml` — Jekyll-Config

## Update-Workflow

1. Markdown bearbeiten (`index.md` oder `support.md`)
2. Datum im Header bei inhaltlichen Änderungen anpassen
3. Commit + push auf `main`
4. GitHub Pages baut innerhalb ~1 Minute neu

Brand-Tokens und Typografie liegen im Layout selbst — synchron zu `docs/brand.md` der App.
