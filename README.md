# Mobico Daily Auction demo

Klikbaar prototype met voorbeeldgegevens. Biedingen worden alleen in de browser opgeslagen.

## Gratis publiceren op GitHub Pages

1. Maak op GitHub een nieuwe **Public** repository: `mobico-daily-auction`.
2. Pak dit ZIP-bestand uit. Upload de bestanden en de map `assets` naar de hoofdmap van de repository. `index.html` moet direct in de hoofdmap staan.
3. Ga naar **Settings → Pages**.
4. Kies bij **Source**: **Deploy from a branch**.
5. Selecteer branch **main**, map **/ (root)** en klik **Save**.
6. De site verschijnt op `https://GEBRUIKERSNAAM.github.io/mobico-daily-auction/`.

Bewerk HTML, CSS of JavaScript in GitHub en commit de wijzigingen om de website bij te werken.
De originele ChatGPT-site wordt hierdoor niet verwijderd.
Biedingen uit de oude site worden niet automatisch meegenomen naar de nieuwe URL.

## Bestanden

- `index.html`: paginastructuur en tabbladen
- `styles.css`: vormgeving
- `app.js`: filters, navigatie, biedingen en CSV-export
- `seed.js`: voorbeeldmodellen en prijzen
- `assets/reference.png`: bestaand beeldbestand voor de logo-uitsnede

Er zijn geen buildstappen, API-sleutels of server nodig. Het lettertype wordt via Google Fonts geladen; bij onbeschikbaarheid wordt Arial gebruikt.
