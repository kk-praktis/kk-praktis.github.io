# Spiele entwickeln mit Javascript, HTML und CSS

## Level 1 : Basics

- Erstelle eine Seite mit einem Button „Cookie“ und einer Zähleranzeige.
- Jedes Klick-Event erhöht den Zähler um 1.

> Schaue dir hierfür `document.getElementById`, `document.querySelector` und `addEventListener` an

## Level 2 : Upgrades einbauen

- Füge einen „Upgrade“-Button hinzu, der z. B. 10 Cookies kostet und pro Klick +2 statt +1 gibt.
- Zeige Kosten dynamisch an, deaktiviere den Button, wenn der Spieler nicht genug Cookies hat.

> Schaue dir hierfür `if/else-Bedingungen` und `innerText` oder `textContent`an

## Level 3 : Cookies pro Sekunde

### Das Ziel in diesem Level ist, dass das Spiel auch ohne den Spieler weitergeht.

- Baue ein Autoclicker Upgrade Button, der alle X Sekunden Cookies hinzufügt. Dieses Upgrade musst natürlich etwas teurer sein.
- Jedes Mal wenn der Spieler genug Cookies hat kann er/sie den Button drücken und bekommt dann pro Sekunde automatisch mehr Cookies
- Das Upgrade muss nach jedem Kauf teurer werden. Überlege dir eine Formel mit der, das Upgrade immer teurer wird.

Zum Beispiel:

cost = baseCost \* Math.pow(multiplier, level)

> Schaue dir hierfür das `Math`-Modul von Javascript, `setInterval` und `clearInterval` an

## Level 4 : Achievements

- Baue Achievements ein die angezeigt werden, wenn der Spieler sie freigeschaltet hat.

### Beispiele für Achievements

- 100 Clicks
- 10 Upgrades gekauft
- 10000 Cookies
- Überleg dir gerne weitere Achievements

> Schaue dir hierfür `Arrays`, `Objekte` und `Zustand-Check-Funktionen` an

## Level 5 : Benutzeroberfläche

- Baue eine CSS-Animation ein, die abgespielt wird bei jedem Click
- Sound-Effekte
- Design das Spiel so wie es dir gefällt

> Schaue dir hierfür einfaches (!) `CSS` an

## Level 6 : Easter Eggs und weitere Mini-Features

- Kleine Zufalls-Events: z. B. zähtl jeder Click doppelt für 10 Sekunden
- Nach X Clicks blinkt der Hintergrund oder ein verstecktes Mini-Spiel öffnet sich

> Schaue dir hierfür `Math.random()` an

## Level 7 : Speichern

- Speichere Highscore, Klickzahl, gekaufte Upgrades und Achievements im `localStorage`.
- Lade den State beim Start und passe die Benutzeroberfläche an. Zeig dem Nutzer an welche Upgrades schon gekauft wurden

> Schaue dir hierfür `JSON`, `localStorage`und `Serialiserung`an
