# BALLON INSTRUMENT – prototyp nového webu

Statický prototyp homepage pro [ballon.cz](https://www.ballon.cz/) podle zadání (TZ v projektu).

## Struktura
- `index.html` – celá stránka (CSS + JS uvnitř)
- `img/` – fotografie (hala s lampou, galerie g01–g12, energetická síť)
- `_headers` – bezpečnostní hlavičky pro Cloudflare Pages / Netlify
- `.nojekyll` – pro GitHub Pages

## Spuštění
Stačí otevřít `index.html` v prohlížeči, nebo zapnout GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

## Před spuštěním ostré verze
- Úvodní hala je ilustrační AI vizualizace – případně nahradit fotkou skutečné zkušebny Ballon.
- Doplnit originály galerie ve vyšším rozlišení, skutečná čísla a případové studie.
- Schválit texty Zásad cookies a GDPR.
- Fonty a knihovny (GSAP, Lenis) hostovat lokálně.
- Formulář napojit na serverové odeslání s antispamem (Turnstile).
