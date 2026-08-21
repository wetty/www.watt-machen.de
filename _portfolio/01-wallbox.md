---
title: Wallbox smart machen
subtitle: Damit Ihre Wallbox das macht was sie soll.
image: assets/img/portfolio/wallbox_400-267.png
alt: evcc

caption:
  title: Wallbox smart machen
  subtitle: Echtes Überschuss Laden. Kein entleeren des Speichers.
  thumbnail: assets/img/portfolio/wallbox_400-267.png
---

Es gibt viele unterschiedliche Wallboxen auf dem Markt. Welche die einfach nur laden und welche die intelligent laden, sprich nur den überschüssigen Strom zum laden verwenden.

In den meisten Fällen wird ein zusätzlicher Zähler mit der Wallbox installiert, der direkt hinter dem offiziellen Stromzähler sitzt. Misst dieser Zähler einen Überschuss, dann nimmt die Wallbox diesen zum laden des Autos.

## Problem ##

Ist Die PV Anlage auch mit einem Stromspeicher ausgerüstet, so kommt es bei dieser Anbindung oftmals vor, dass die Wallbox den Speicher entlädt. Problem ist ganz einfach das der Speicher und die Wallbox nicht miteinander verbunden sind, und sich so quasi nicht absprechen können wer denn nun überschüssigen Strom zum laden nimmt.

## Lösung ##

Es gibt eine Software Namens [evcc](https://evcc.io/), die alle Komponenten miteinander verbindet. Damit lässt ganz klar regeln was zuerst geladen wird. Also ob das eAuto vorrang vor dem Hauptspeicher hat, oder umgedreht. Oder ob das eAuto dran kommt wenn der Hausspeicher mindestens zu 80% gefüllt ist.

Aber es gibt natürlich noch mehr Möglichkeiten. So läßt sich die Stromtarif hinterlegen und festlegen, das z.B. bei einem dynamischen Tarif erst aus dem Netz geladen wird, wenn der Strompreis unter 21ct/kWh ist.

Für evcc brauchen Sie nur einen kleinen Server (größe einer Zigarettenpackung), auf dem die Software rund um die Uhr läuft. 

Keine Angst, ich liefere Ihnen alles fertig eingerichtet zum ausprobieren.
