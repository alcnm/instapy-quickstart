# Alya und Mustafa Dayi Spiel – Endlosstraße

Ein kleines Browser-Spiel in einfachem HTML/CSS/JavaScript.

## Start lokal

1. Öffne `alia-game/index.html` direkt im Browser.
2. Klicke auf **Start**.
3. Bewege die Katze nur mit **Links/Rechts** oder **A/D**.

## Spielidee

- Eine gerade Straße in Perspektive bewegt sich endlos auf dich zu.
- Die Straße hat einen ruhigen bunten Boden aus farbigen Quadraten (ohne verwirrende Mittellinie).
- Mäuse und Fallen kommen auf dich zu.
- Ziel: Mäuse fangen und Fallen vermeiden.
- Bei jeder gefangenen Maus wird die Katze größer.
- Wenn die Katze eine Falle berührt: **Punkte zurück auf 0**, Katze wieder klein und 1 Leben weniger.
- Die Katze hat insgesamt 3 Leben. Bei 0 Leben ist **Game Over**.
- Eine Runde dauert 60 Sekunden (ein Level).
- Am Straßenrand stehen nun größere Menschen und Bäume sowie Häuser, damit es wie eine kleine Stadt wirkt.
- Levelsystem nach gesammelten Mäusen:
  - Ab 10 Mäusen: **Level 2** (Mäuse bewegen sich manchmal seitlich).
  - Ab 20 Mäusen: **Level 3** (Mäuse und Fallen bewegen sich manchmal seitlich).
  - Ab 30 Mäusen: **Level 4** (zusätzlich laufen gelegentlich Menschen über die Straße).
