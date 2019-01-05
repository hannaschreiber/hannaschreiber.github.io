---
layout: post
title: Planungstool für Temperaturdecken
date: 2019-01-05 21:48:00 +0100
categories: häkeln
---

# Planungstool für Temperaturdecken

Nachdem ich meinem Mann von meiner Idee, eine Temperaturdecke zu häkeln, vorgeschwärmt habe, kam er auf die Idee, ein Planungstool dafür zu bauen. Er hat Informatik studiert und er liebt es, sich solche Hilfen auszudenken. Das ganze nennt sich temperature heatmap und jeder kann es einsehen und benutzen.
Wenn du die Decke für ein vergangenes Jahr machst (also die Temperaturen weißt), wird dir das fertige Streifenmuster der Decke angezeigt. Aber auch wenn du für das aktuelle Jahr häkelst, kannst du dir damit anschauen, welche Farben gut zusammenpassen.

[Hier ist der Link!](https://codepen.io/anon/pen/WLMXYV?editors=0010) (hier sind beispielhaft die Wetterdaten von 1990 hinterlegt und die Farben, die ich mir für meine Decke überlegt habe)

## Und so funktionert es

Für eine bessere Übersicht kannst du die Bereiche mit HTML und CSS zusammenschieben. Wir brauchen nur das Fenster mit JS.



![Bild Planungstool_Temperaturbereich-Farbname](/assets/Planungstool_Temperaturbereich-Farbname.JPG)

Hier oben gibst du deine Temperaturschritte und die dazugehörigen Farben ein. Die Farben gehen entweder als HEX-Codes oder viele der Farben haben auch Namen, die der Browser verarbeiten kann. Welche Farbnamen es gibt, siehst du beispielsweise [hier](https://www.w3schools.com/tags/ref_colornames.asp).



![Bild Planungstool_Wertetabelle.JPG](/assets/Planungstool_Wertetabelle.JPG)

Hier trägst du deine Wetterdaten ein. Ich habe meine von [wetterkontor.de](https://www.wetterkontor.de/), da konnte ich einfach die ganze Tabelle reinkopieren. Pass nur auf, dass du die Apostrophe zu Beginn und Ende deines Eintrags nicht überschreibst bzw. du sie dann neu hinschreibst. Sonst kann der Browser das nicht lesen.



![Bild Planungstool_Spalte-angeben.JPG](/assets/Planungstool_Spalte-angeben.JPG)

In deiner Temperaturwertetabelle tauchen ja wahrscheinlich mehrere Werte für einen Tag auf: Tiefstwert, Höchstwert, Mittelwert. Jetzt kannst du angeben, aus welcher Spalte der Tabelle der Browswer sich die Werte nehmen soll. Da, wo die orange 2 steht, schreibst du die Nummer der Spalte rein. In meinem Fall stehen in Spalte 2 die Höchstwerte.



![Bild Planungstool_Funktion.JPG](/assets/Planungstool_Funktion.JPG)

This is where the magic happens. (Ich habe keine Ahnung, wie, aber es klappt.) :-)



![Bild Planungstool_Farben.JPG](/assets/Planungstool_Farben.JPG)

Und Bäääm! Dieses Muster wird die Decke dann haben, wenn sie fertig ist. 

Du kannst deine Eintragungen speichern. Über den Link oben in der Browserzeile kommst du dann später wieder zu deiner Seite zurück. Wenn du dir mehrere verschiedene Farbschemen/Temperatureinteilungen/Jahre speichern willst, geht das nur mit einem Account bei Codepen. Sonst werden deine vorherigen Eintragungen immer wieder überschrieben.
