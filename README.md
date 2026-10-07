# Phase 10 Master – Wertungsblatt

Digitale Punkteliste für **Phase 10 Master**. Läuft als App auf dem iPad, der Spielstand bleibt gespeichert.

**App:** https://xman-berlin.github.io/phase10-master/

## Installation

Auf dem iPad/iPhone: Link öffnen → Teilen → **Zum Home-Bildschirm**.  
Im Browser: „App installieren“, falls angeboten.

## Funktionen

- 2–6 Spieler, Namen über eigene Tastatur (kein iPad-Keyboard)
- Runde eintragen mit Plus/Minus; genau eine Person „Aus“ (0 Punkte, Phase geschafft)
- Letzte Runde korrigieren
- Gewinner als Karte in der Mitte (antippen schließt sie), plus kurzes Konfetti
- Danach neues Spiel – keine weiteren Runden mehr im beendeten Spiel
- Hell- und Dunkelmodus
- Offline (PWA), Stand in `localStorage`

## Regeln in der App

- Phasen nur der Reihe nach
- Wer zuerst alle 10 Phasen hat, gewinnt; bei mehreren die wenigsten Minuspunkte
- Jede Restkarte zählt 1 Minuspunkt
