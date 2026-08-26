---
slug: Wallbox smart machen
title: Wallbox smart machen
subtitle: Damit Ihre Wallbox das macht was sie soll.
image: https://imgproxy.wetterer.de/insecure/format:webp/plain/https://watt-machen.de/assets/img/portfolio/wallbox_400-267.png
alt: evcc

caption:
  title: Wallbox smart machen
  subtitle: Echtes Überschuss Laden. Kein entleeren des Speichers.
  thumbnail: https://imgproxy.wetterer.de/insecure/format:webp/plain/https://watt-machen.de/assets/img/portfolio/wallbox_400-267.png
---

Die Auswahl an Wallboxen ist mittlerweile sehr groß. Neben einfachen Modellen, die das Fahrzeug lediglich laden, gibt es auch intelligente Wallboxen. Diese können beispielsweise erkennen, wann überschüssiger Solarstrom zur Verfügung steht, und diesen gezielt zum Laden des Elektrofahrzeugs nutzen.

In den meisten Fällen wird hierfür ein zusätzlicher Energiezähler installiert. Dieser befindet sich üblicherweise direkt hinter dem offiziellen Stromzähler des Netzbetreibers und misst den aktuellen Stromfluss am Hausanschluss.

Wird ein Stromüberschuss erkannt, gibt die Wallbox die entsprechende Ladeleistung an das Fahrzeug weiter. Dadurch wird bevorzugt selbst erzeugter Solarstrom genutzt, anstatt ihn ins öffentliche Netz einzuspeisen.

## Das Problem

Wird die Photovoltaikanlage zusätzlich mit einem Batteriespeicher betrieben, entsteht häufig ein unerwünschter Effekt:

Die Wallbox erkennt zwar einen verfügbaren Stromüberschuss, weiß jedoch nicht, ob dieser tatsächlich direkt von der PV-Anlage kommt oder aus dem Batteriespeicher bereitgestellt wird.

Da Speicher und Wallbox in vielen Anlagen unabhängig voneinander arbeiten und nicht miteinander kommunizieren, kann es passieren, dass das Elektroauto den Hausspeicher entlädt. Statt überschüssigen Solarstrom zu nutzen, wird dann wertvolle Energie aus dem Speicher ins Fahrzeug übertragen.

Das Ergebnis:

- Der Hausspeicher wird unnötig entladen.
- Die gespeicherte Energie steht später für den Haushalt nicht mehr zur Verfügung.
- Der Eigenverbrauch wird nicht optimal gesteuert.
- Das Energiesystem arbeitet weniger effizient.

## Die Lösung

Mit der Open-Source-Software **EVCC** ([https://evcc.io](https://evcc.io)) lassen sich Photovoltaikanlage, Batteriespeicher, Wallbox und Stromzlligenten Gesamtsystem verbinden.

EVCC übernimmt die zentrale Steuerung aller Komponenten und sorgt dafür, dass diese miteinander kommunizieren. Dadurch können individuelle Regeln für das Energiemanagement festgelegt werden.

Beispiele:

- Das Elektroauto hat Vorrang vor dem Hausspeicher.
- Der Hausspeicher hat Vorrang vor dem Elektroauto.
- Das Fahrzeug wird erst geladen, wenn der Batteriespeicher mindestens 80 % geladen ist.
- Es wird ausschließlich überschüssiger Solarstrom zum Laden verwendet.
- Es wird ein Mindestladestand des Fahrzeugs bis zu einer bestimmten Uhrzeit sichergestellt.

## Dynamische Stromtarife

EVCC kann zusätzlich dynamische Stromtarife berücksichtigen.

Dadurch lassen sich intelligente Strategien umsetzen, beispielsweise:

- Laden des Elektroautos nur bei günstigen Strompreisen.
- Netzladung des Speichers während besonders günstiger Tarifzeiten.
- Automatische Nutzung der jeweils wirtschaftlichsten Energiequelle.
- Kombination von PV-Überschuss und günstigen Netzstrompreisen.

So könnte beispielsweise festgelegt werden, dass Strom erst dann aus dem Netz bezogen wird, wenn der Preis unter **21 Cent pro kWh** liegt.

## Die Hardware

Für den Betrieb von EVCC wird lediglich ein kleiner, stromsparender Server benötigt. Häufig kommt hierfür ein Mini-PC oder ein Raspberry Pi zum Einsatz, der ungefähr die Größe einer Zigarettenschachtel hat.

Die Software läuft rund um die Uhr und übernimmt vollautomatisch die Steuerung des gesamten Energiesystems.

## Ihr Vorteil

Mit einer intelligenten Steuerung erhalten Sie deutlich mehr aus Ihrer Photovoltaikanlage:

- Maximaler Eigenverbrauch des selbst erzeugten Stroms
- Optimale Abstimmung zwischen PV-Anlage, Speicher und Wallbox
- Geringere Stromkosten
- Höhere Unabhängigkeit vom Energieversorger
- Priorisierung nach Ihren individuellen Bedürfnissen
- Zukunftssichere Lösung für weitere Energiesysteme wie Wärmepumpen oder zusätzliche Speicher

> **Keine Sorge:** Sie müssen sich nicht selbst um die Einrichtung kümmern. Auf Wunsch erhalten Sie ein komplett vorkonfiguriertes System, das sofort einsatzbereit ist und in Ihrer Anlage getestet werden kann.