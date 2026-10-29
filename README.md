# Onyx.AI – Website (Ausweich-Adresse)

Statischer Export der Website aus `claude-onyx-portfolio-site-yivzqd/onyx-3d` (`next build`, `output: "export"`).
Läuft über GitHub Pages unter https://marvinvoicelink-ai.github.io, solange onyx-ai.de bei STRATO gesperrt ist.

Hinweis: Das Kontaktformular nutzt Netlify Forms und funktioniert hier nicht.

## Beispiele für Interessenten (`/beispiele/`)

`beispiele/` gehört **nicht** zum Next-Export und muss bei jedem neuen Deploy erhalten bleiben
(beim Leeren des Repos also `.git`, `README.md`, `.nojekyll` **und** `beispiele/` stehen lassen).

- `beispiele/index.html` – Zeitraffer, Vorher/Nachher-Regler, Drohnenflug, Link zur Scroll-Website
- `beispiele/finca/` – anonymisierte Scroll-Website der Finca (Spanisch)
- `beispiele/ONYX-Studio-Infoblatt.pdf` – das Infoblatt, auf das die QR-Codes zeigen

Beide Seiten haben `noindex`, damit sie nicht in Suchmaschinen landen.
