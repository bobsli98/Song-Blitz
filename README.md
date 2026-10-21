# Song-Blitz

Musik-Ratespiel für einen gemeinsamen Bildschirm (Laptop oder Tablet). Ein Song startet, wer ihn erkennt, tippt auf „Erkannt!“ und wählt aus vier Titeln vom selben Album. Je schneller, desto mehr Punkte (1000 bis 100), falsch gibt 0.

## Einrichtung

1. **GitHub Pages:** Settings → Pages → Source „Deploy from a branch“, Branch `main`, Ordner `/ (root)`.
   Die Seite läuft dann unter `https://bobsli98.github.io/Song-Blitz/`.
2. **Spotify-App** im [Developer Dashboard](https://developer.spotify.com/dashboard):
   - Redirect URI: `https://bobsli98.github.io/Song-Blitz/`
   - APIs: Web API und Web Playback SDK
3. Seite öffnen, mit Spotify verbinden (Premium nötig) und eure Playlist aus der Liste wählen (oder per Link einfügen).
   Die Playlist muss dir gehören oder du musst dort mitarbeiten.

Die Client-ID kann auch fest in `index.html` bei `CONFIG.clientId` eingetragen werden.

## Modi & Extras

- **Reihum:** Jeder rät allein, etwa jede fünfte Runde ist eine Bonusrunde für alle.
- **Duell:** Immer zwei Spieler gegeneinander mit eigenem Buzzer (Tasten = Spielernummer).
- **Serien-Bonus:** Ab dem 3. Treffer in Folge +100, +200, max. +300 Extra-Punkte.
- **Siegerehrung** mit Trommelwirbel, Podest und Auszeichnungen. Soundeffekte lassen sich oben über 🔊 ausschalten.

## Hinweise

- Während ein Song läuft, zeigt das Spiel keinen Titel. Schliesst die Spotify-App auf anderen Geräten, sonst steht er dort.
- Etwa jede fünfte Runde ist eine Bonusrunde: Alle raten mit (Buttons oder Tasten 1–9), Punkte wie in normalen Runden. Wer falsch liegt, verliert 200 Punkte und ist raus, alle anderen bekommen 100.
- Ohne Spotify gibt es einen Demo-Modus mit erfundenen Melodien.
