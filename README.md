# Die Love-Chronik — Geburtstags-Sonderausgabe

Eine romantische, deutschsprachige Noir-Zeitung als interaktives Flipbook für **Love**.

## Start

`index.html` im Browser öffnen. Es gibt keinen Build-Schritt und keine externen JavaScript-Abhängigkeiten.

## Bedienung

- Auf dem Handy: nach links/rechts wischen oder die Pfeile benutzen.
- Auf Desktop: linke/rechte Hälfte der Zeitung anklicken oder `←` / `→` verwenden.
- `Home` / `End` springen an Anfang/Ende.
- `M` schaltet die Musik stumm bzw. wieder ein.
- Die Spinne oben rechts reagiert auf Antippen.

## Enthaltene Bilder

- `love.webp` — Beweisstück A, erste Bleistiftskizze.
- `love2.webp` — Beweisstück B, zweite Bleistiftskizze.

Die WebP-Dateien sind für schnelle mobile Ladezeiten optimiert, ohne die Auflösung der generierten Skizzen zu reduzieren.

## Responsive Verhalten

Das Layout verwendet einen festen Designraum pro Seite und skaliert ihn proportional in den verfügbaren Viewport. Auf schmalen Geräten wird eine Seite nach der anderen gezeigt; im Querformat und auf Desktop werden passende Spread-Modi verwendet. Lange Inhalte besitzen zusätzlich eine automatische Shrink-to-fit-Sicherung gegen Abschneiden.
