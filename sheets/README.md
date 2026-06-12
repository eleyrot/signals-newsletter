# Google Sheets Vorlage — Speicher direkt

## Schritt 1: Sheet anlegen

1. Geh zu: https://sheets.new
2. Benenne die Datei: **Speicher direkt — Redaktion**
3. Erstelle folgende 3 Tabs (unten auf "+" klicken):

---

## Tab 1: Staging

Erste Zeile = Spaltenköpfe (fett, einfrieren):

| A | B | C | D | E | F | G | H |
|---|---|---|---|---|---|---|---|
| Datum | Quelle | Titel | Text | Link | Bild-URL | Sektion | Freigabe |

**Sektion-Werte:** gemeinderat / bau / abstimmung / amtsblatt / agenda / vereine  
**Freigabe-Werte:** OFFEN / FREIGEGEBEN / ABGELEHNT

---

## Tab 2: Agenda

| A | B | C | D | E | F | G | H |
|---|---|---|---|---|---|---|---|
| Eingangsdatum | Verein | Titel | Beschreibung | Datum | Ort | Kontakt | Freigabe |

---

## Tab 3: Archiv

| A | B | C | D | E |
|---|---|---|---|---|
| Ausgabe | Datum | Betreff | Status | Brevo-Campaign-ID |

---

## Schritt 2: Sheet-ID notieren

Die Sheet-ID findest du in der URL:  
`https://docs.google.com/spreadsheets/d/`**HIER-IST-DIE-ID**`/edit`

Diese ID brauchst du in Make.com für alle Flows.
