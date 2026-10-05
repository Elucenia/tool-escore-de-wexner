<!-- ELUCENIA technical documentation · escore-de-wexner · de · no clinical/professional/rights approval -->

# Wexner-Score (Stuhlinkontinenz)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/escore-de-wexner)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Unwillkürlicher Abgang festen Stuhls

`solido`

- `0` — Nie
- `1` — Selten (weniger als 1 Mal pro Monat)
- `2` — Manchmal (weniger als 1 Mal pro Woche, mindestens 1 Mal pro Monat)
- `3` — Häufig (weniger als 1 Mal pro Tag, mindestens 1 Mal pro Woche)
- `4` — Immer (1-mal täglich oder häufiger)

### Unwillkürlicher Abgang flüssigen Stuhls

`liquido`

- `0` — Nie
- `1` — Selten (weniger als 1 Mal pro Monat)
- `2` — Manchmal (weniger als 1 Mal pro Woche, mindestens 1 Mal pro Monat)
- `3` — Häufig (weniger als 1 Mal pro Tag, mindestens 1 Mal pro Woche)
- `4` — Immer (1-mal täglich oder häufiger)

### Unwillkürlicher Abgang von Gasen

`gas`

- `0` — Nie
- `1` — Selten (weniger als 1 Mal pro Monat)
- `2` — Manchmal (weniger als 1 Mal pro Woche, mindestens 1 Mal pro Monat)
- `3` — Häufig (weniger als 1 Mal pro Tag, mindestens 1 Mal pro Woche)
- `4` — Immer (1-mal täglich oder häufiger)

### Verwendung von Einlage oder Slipeinlage

`protetor`

- `0` — Nie
- `1` — Selten (weniger als 1 Mal pro Monat)
- `2` — Manchmal (weniger als 1 Mal pro Woche, mindestens 1 Mal pro Monat)
- `3` — Häufig (weniger als 1 Mal pro Tag, mindestens 1 Mal pro Woche)
- `4` — Immer (1-mal täglich oder häufiger)

### Änderung der Lebensführung

`estilo`

- `0` — Nie
- `1` — Selten (weniger als 1 Mal pro Monat)
- `2` — Manchmal (weniger als 1 Mal pro Woche, mindestens 1 Mal pro Monat)
- `3` — Häufig (weniger als 1 Mal pro Tag, mindestens 1 Mal pro Woche)
- `4` — Immer (1-mal täglich oder häufiger)

## Fassung der Methode

Cleveland Clinic/Wexner Jorge 1993: 5 Merkmale 0–4, Gesamt 0–20; Stuhlinkontinenz

## Dokumentierte Formel

Jedes der 5 Merkmale erhält 0 bis 4 nach Häufigkeit: nie (0); selten, weniger als 1-mal pro Monat (1); manchmal, weniger als 1-mal pro Woche und mindestens 1-mal pro Monat (2); gewöhnlich, weniger als 1-mal pro Tag und mindestens 1-mal pro Woche (3); immer, mindestens 1-mal pro Tag (4).

Gesamt 0 (vollständige Kontinenz) bis 20 (vollständige Inkontinenz).

## Grenzen und Population

Die berichtete Schwere der Stuhlinkontinenz bestimmt weder Ursache noch Behandlung. Die Originalübersicht betont Anamnese, Untersuchung und physiologische Beurteilung vor der Behandlung. Skala und Häufigkeiten müssen entsprechend der Version angewendet werden; die Summe ersetzt keine Beurteilung der anorektalen Funktion.

## Referenzen

- [Jorge JM, Wexner SD. Etiology and management of fecal incontinence. Dis Colon Rectum, 1993.](https://doi.org/10.1007/BF02050307)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
