# Deutsch A1 Woordtrainer

Meerkeuze-oefenapp voor Duitse woorden, gevoelens, uitdrukkingen en zinnen.
Werkt offline en kan als app op je telefoon gezet worden.

## Op GitHub Pages zetten
1. Maak op github.com een nieuwe repository, bijv. `duits-trainer` (Public).
2. Klik **Add file → Upload files** en sleep alle bestanden uit deze map erin. **Commit**.
3. Ga naar **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `(root)` → **Save**.
4. Na ±1 minuut staat de app op `https://<jouw-gebruikersnaam>.github.io/duits-trainer/`.

## Op je telefoon
- **iPhone (Safari):** open de link → deel-knop → *Zet op beginscherm*.
- **Android (Chrome):** open de link → ⋮ → *App installeren* / *Toevoegen aan startscherm*.

## Woorden toevoegen
Open `words.js` en voeg een regel toe:
`["gevoel", "verärgert", "geïrriteerd", "optionele tip"],`
Verhoog daarna in `sw.js` de `VERSION` (bijv. "v2") zodat je telefoon de update ophaalt.
