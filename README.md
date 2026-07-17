# STPLS. — Mike's Vegan Staples

Eine persönliche, redaktionelle Affiliate-Discovery-Seite für vegane Basics — plus der ursprüngliche TWELVE-B12-Pre-Launch-Prototyp.

Die Startseite ist als schneller Instagram-Bio-Funnel optimiert: persönlicher Creator-Kontext, mobile Schnelleinstiege zu B12, Omega-3 und Kreatin, eine kompakte Sticky-Navigation und Social-Preview-Metadaten.

## Seiten

- `index.html`: STPLS. mit kuratiertem Stack, Filtern und transparenter Affiliate-Logik
- `b12.html`: TWELVE — B12. Erledigt.

## Affiliate-Links einsetzen

In `index.html` befindet sich am Ende der Konfigurationsblock `AFFILIATE_LINKS`. Dort können die echten Partner-URLs für Omega-3, Vitamin D, Kreatin, Magnesium, Olivenöl, funktionale Pilze und Jod eingetragen werden.

Solange ein Wert leer ist, öffnet der jeweilige Button transparent einen Platzhalter-Dialog. Sobald eine URL hinterlegt ist, öffnet sie sich in einem neuen Tab und wird technisch mit `rel="sponsored noopener"` gekennzeichnet.

## TWELVE-Konzept

TWELVE verkauft nicht einfach eine weitere Dose Supplements. Die Idee ist eine **Nie-ohne-Garantie**:

- ein geprüfter Jahresvorrat
- rechtzeitiger Nachschub
- klare, verständliche Information
- faire Preisstufen von Access bis Household
- transparente Chargenanalysen statt leerer Qualitätsversprechen

## Preisstufen im Prototyp

| Mitgliedschaft | Preis | Idee |
| --- | ---: | --- |
| Access | 12 €/Jahr | Niedrige Zugangshürde ohne Nachweispflicht |
| Essential | 18 €/Jahr | Fairer Standardpreis |
| Solidarity | 30 €/Jahr | Unterstützt Access-Mitgliedschaften |
| Household | 49 €/Jahr | Jahresversorgung für bis zu vier Menschen |

## TWELVE Lab

Die Landingpage testet ausserdem unverbindliches Interesse an:

- veganem Algen-Omega-3
- veganem Vitamin D3
- Kreatin-Monohydrat
- Magnesium
- hochpolyphenolhaltigem Olivenöl
- funktionalen Pilzprodukten

Die Auswahl wird im aktuellen Prototyp nur lokal im Browser gespeichert. Es werden noch keine Daten an einen Server gesendet.

## Lokal öffnen

Das Projekt benötigt keinen Build-Schritt und keine Abhängigkeiten.

1. `index.html` direkt im Browser öffnen, oder
2. im Projektordner `python3 -m http.server 8000` ausführen und `http://localhost:8000` besuchen.

## Status

Pre-Launch-Konzept. Vor Veröffentlichung sind echte Affiliate-Partner, finale Linkkennzeichnung, Impressum, Datenschutz und ein echtes Newsletter-Backend erforderlich. Vor einem eigenen Produktstart kommen Markenprüfung, Lebensmittelrecht, Rezeptur, Herstellerqualifizierung und Laborprüfung hinzu.

## Medizinischer Hinweis

Dieses Projekt ist keine medizinische Beratung. Nahrungsergänzungsmittel sind kein Ersatz für eine ausgewogene Ernährung. Bei bekanntem Mangel, Resorptionsstörungen, Beschwerden oder relevanten Erkrankungen gehört die Versorgung in fachliche Hände.
