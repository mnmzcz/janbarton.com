# janbarton.com

Statický web [janbarton.com](https://janbarton.com), hostovaný na Vercelu.
Každý push na `main` se automaticky nasadí.

Obsah je statický export (Next.js) stažený z produkce 5. 11. 2026 – úpravy se dělají přímo v HTML.

- `vercel.json` – bezpečnostní hlavičky (stejné jako na původním hostingu), cache
- `404.html` – vlastní chybová stránka

## Vercel
Add New → Project → `mnmzcz/janbarton.com`, Framework Preset: **Other**, bez build příkazu, Output Directory `.` (výchozí).
