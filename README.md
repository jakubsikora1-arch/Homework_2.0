# Domácí spotřebiče — Homework Helper

Jednoduchá webová aplikace pro doporučení nastavení grilu a programu pračky.

## Soubory

Všechny soubory aplikace jsou v kořenovém adresáři repozitáře (bez podsložky `assets/`):

- `index.html` — vstupní stránka (malá písmena kvůli GitHub Pages)
- `app.js` — logika aplikace
- `styles.css` — styly
- `wash.json` — data programů pračky
- `homework-helper.svg` — vektorová ikona a favicon
- `homework-helper-180.png` — ikona pro plochu iPhonu
- `homework-helper-192.png`, `homework-helper-512.png` — ikony pro instalaci PWA
- `manifest.webmanifest` — název, ikony a režim samostatné aplikace

## Nasazení na GitHub Pages

1. Nahraj všechny soubory z tohoto adresáře přímo do kořenového adresáře větve/adresáře, ze kterého GitHub Pages publikuje web.
2. V nastavení repozitáře otevři **Settings → Pages** a nastav zdroj publikování.
3. Počkej na zveřejnění webu. Pro přidání na plochu musí být aplikace dostupná přes HTTPS.

## Přidání ikony na plochu iPhonu

1. Otevři zveřejněnou adresu aplikace v **Safari** (ne pouze v prohlížeči uvnitř jiné aplikace).
2. Klepni na **Sdílet**.
3. Vyber **Přidat na plochu**. Pokud je nabídka dostupná, zapni volbu **Otevřít jako webovou aplikaci**.
4. Potvrď tlačítkem **Přidat**.

Ikona se načítá z `./homework-helper-180.png` a manifest i ostatní ikony jsou rovněž v kořenovém adresáři. Relativní cesty fungují i při publikování projektu v podadresáři GitHub Pages.

Poznámka: ikonu na ploše nelze vytvořit pouhým otevřením lokálního HTML souboru. Stránka musí být dostupná přes webovou adresu; pro GitHub Pages se používá HTTPS.
