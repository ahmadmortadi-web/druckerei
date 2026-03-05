# Allaoui – Landing Page Mockups

**Branch:** `nuovoweb` | **Projekt:** Insolvenz-Landing-Pages für Allaoui Graphic Machinery GmbH

Dieses Repository enthält HTML-Mockups für die neue Landing-Page-Kampagne der **Allaoui Graphic Machinery GmbH**, einem international tätigen Spezialisten für den Handel, die Bewertung und die Verwertung von Druck- und Medienmaschinen mit Sitz in Aachen.

---

## Über das Projekt

Die Landing Pages richten sich primär an **Insolvenzverwalter und Eigenverwalter**, die Maschinenparks aus der Druck- und Medienbranche schnell und professionell verwerten müssen. Allaoui bietet dabei die komplette Abwicklung aus einer Hand – vom Erstgespräch bis zur besenreinen Übergabe der Immobilie.

**Kernbotschaft:** *Wir übernehmen Ihren Maschinenpark. Komplett. Sofort. En bloc.*

---

## Dateien im Repository

| Datei | Beschreibung |
|---|---|
| `mockup1-authority.html` | Mockup 1 – „Authority"-Variante mit TailwindCSS, großformatigem Hero, KPI-Leiste, Referenzkarten mit Fotos, 6-Schritte-Timeline, Leistungsübersicht, Über-uns-Sektion und Kontaktbereich |
| `mockup_a.html` | Mockup A – Kompaktes, mobil-optimiertes Design mit Alpine.js, Why-Cards (inkl. „featured"-Highlight), Prozess-Steps, Leistungsliste und Kontaktkarte |
| `mockup_c.html` | Mockup C – Weiteres Layoutkonzept mit Sticky-Nav, weißem Hintergrund und angepasstem Farbschema |
| `mockup_d.html` | Mockup D – Variante mit „Acumin Pro Wide"-Typografie, schmalem 800px-Layout und heller Navigation |

---

## Seitenstruktur

Alle Mockups teilen dieselbe inhaltliche Struktur:

1. **Hero** – Kernversprechen, Subtext und CTA-Button
2. **KPI-Leiste** – 40.000+ Marktdatensätze, 12+ Großprojekte, 2 Monate schnellste Räumung, XX Mio. € Transaktionsvolumen
3. **Warum Allaoui** – 5 Vertrauensargumente für Insolvenzverwalter
4. **Referenzen** – CPI Ebner & Spiegel (Ulm), Schreckhase (Spangenberg), Stürtz (Würzburg), TSB Bagel (Meineweh), Eberl & Kösel (Allgäu), Qubus Media (Hamburg)
5. **Prozess-Timeline** – 6 Schritte: Erstgespräch → Besichtigung → Angebot → Demontage → Übergabe → Dokumentation
6. **Leistungen** – Bewertung, En-bloc-Erwerb, Vermarktung/Versteigerung, Räumung, Sanierung/Beteiligung
7. **Über uns** – Profil der Allaoui Graphic Machinery GmbH, Aachen
8. **Kontakt** – Omar Allaoui, Geschäftsführer; Nerscheider Weg 170, 52076 Aachen

---

## Technologien

- **HTML5** (`lang="de"`) – vollständig statische Seiten, keine Build-Pipeline erforderlich
- **TailwindCSS** via CDN – `mockup1-authority.html`
- **Alpine.js** via CDN – `mockup_a.html`
- **Vanilla CSS** – `mockup_c.html` und `mockup_d.html`
- **Google Fonts (Inter)** – `mockup1-authority.html`
- **Inline SVG Icons** – alle Varianten

---

## Farbpalette

| Variable | Hex | Bedeutung |
|---|---|---|
| `--trustful-blue` | `#100C34` | Primärfarbe (Dunkelblau) |
| `--innovative-blue` | `#007DFF` | Akzentfarbe (Hellblau) |
| `--steel-blue` | `#E4F2FF` | Hintergrundfarbe |
| `--inspiring-red` | `#EB0050` | Highlight-Farbe |
| `--green` | `#00B894` | Erfolgsfarbe |

---

## Assets (Platzhalter)

Die HTML-Dateien referenzieren folgende Pfade im Ordner `assets/`, die noch befüllt werden müssen:

- `logo.png` – Allaoui-Logo
- `hall1.jpg`, `hall2.jpg`, `hall3.jpg` – Hallenfotos (innen)
- `machine1.jpg` – Maschinenfotos
- `building1.jpg`, `building2.jpg` – Außenaufnahmen
- Portraitfoto Omar Allaoui (ausstehend)

---

## Lokale Vorschau

Da es sich um rein statische HTML-Dateien handelt, kann jede Datei direkt im Browser geöffnet werden:

```bash
open mockup1-authority.html

# Empfohlen fuer korrekte Asset-Pfade: lokaler Dev-Server
npx serve .
```

---

## Offene Platzhalter (TODOs)

Folgende Inhalte sind in den Mockups noch als Platzhalter markiert:

- `[X]+` – Anzahl abgewickelter Großprojekte
- `[X] Mio.` – Genaues Transaktionsvolumen in Euro
- `[Gruendungsjahr]` – Gründungsjahr der Allaoui GmbH
- `[?] qm` – Lagerkapazität
- `[Telefonnummer]` – Telefonnummer
- `[E-Mail-Adresse]` – E-Mail-Kontakt
- Portraitfoto Geschäftsführer

---

## Unternehmen

**Allaoui Graphic Machinery GmbH**
Nerscheider Weg 170, 52076 Aachen, Deutschland
Web: [www.allaoui.de](https://www.allaoui.de)

---

*Branch `nuovoweb` – Stand: Maerz 2026*
