# Bosnien-Merch-Shop – Projektkontext und Checkliste

Stand: 29.10.2026. Checkboxen beim Erledigen abhaken (`[x]`) und neue Entscheidungen hier nachtragen.
Technische Hinweise zum Theme stehen in `AGENTS.md`.

## Projekt

- **Idee:** ruhiges, hochwertiges Label für die bosnische Diaspora (16–35, v. a. DE, AT, CH, Skandinavien, USA). Vintage-Stickerei, bosnische Lilie, Nostalgie mit Augenzwinkern.
- **Leitspruch:** „you met me at a very bosnian time in my life“
- **Stil:** Schwarz, Anthrazit, Creme. Serifenschrift für Überschriften, viel Leerraum.
- **Erster Entwurf:** `design/mockup-hoodie-v1.png` (KI-Mockup Hoodie: Ranke mit Lilie vorne, Spruch hinten). Lilie ist dort noch eine französische Fleur-de-Lis, und die Ranke ist für Stickerei zu fein.
- **Aktueller Entwurf (30.10.2026):** `design/mockup-longsleeve-v1.png`, erstellt mit `design/masterprompt-longsleeve.txt` und der RBiH-Flagge als Referenz. Vorne mittig eine vereinfachte Ranke (ca. 20 cm breit, Lilienblüte, Knospe, ca. 10 Blätter) mit schlanker bosnischer Lilie wie auf der RBiH-Flagge, hinten der Spruch als Druck. Entscheidung 30.10.: Spruch nur klein unter dem Kragen (ca. 10–12 cm breit, Buchstaben ca. 5–6 mm, als Druck, nicht gestickt), nicht 24 cm breit wie im Mockup v1. Für die Produktionsdatei: Staubfäden weglassen oder verdicken, Lilie auf 3,5–4 cm Höhe vergrößern.
- **Entscheidung 30.10.2026: zwei Longsleeve-Varianten, sonst nichts.**
  - **„Ranke“:** Ranke mit Lilienblüte und Lilie vorne mittig (ca. 20 × 5–6 cm), eher Frauen bzw. unisex
  - **„Ljiljan“:** nur die Lilie, klein auf der linken Brust (ca. 4 cm hoch), eher Männer. Gleiches Stickmotiv wie die Beanie, also nur eine Digitalisierung.
  - Beide mit derselben kleinen Rückenschrift unter dem Kragen.
- **Idee für später (nicht zum Start):** Variante mit Stari Most als Linienzeichnung, Prompt liegt in `design/masterprompt-longsleeve-most.txt`.
- **Bosnische Lilie:** Form wie auf der Flagge der RBiH von 1992: schlank und hoch, mittleres Blatt spitz, kleine eingerollte Seitenblätter, dünnes Band, etwas längerer Fuß. Ähnelt der Fleur-de-Lis, ist aber schlanker.
- **Markenname:** **bihtime** (entschieden am 29.10.2026). Domain: **bihtime.com**, gekauft am 30.10.2026 über Shopify, Hauptdomain des Shops, Kontakt-E-Mail verifiziert, automatische Verlängerung für 16 $/Jahr. Hashtag/Accounts: #bihtime, @bihtime. Variante bih-time.com ebenfalls frei, optional als Weiterleitung.
- **Nicht verwenden:** „Made in BiH“ – Printful produziert nicht in Bosnien, das wäre irreführend.

## Technik

- **Shop:** `rjydix-2b.myshopify.com`, Shopify Basic (3 Monate für 1 €, danach 36 €/Monat)
- **Theme:** Horizon 4.3.0, lokal in diesem Ordner, Git-Repo auf GitHub (AmkoAmin/shopify-shop, privat)
  - Live seit 30.10.2026: „bihtime Design v1“ (ID 209820844369)
  - Sicherung: Original „Horizon“ (ID 209718837585), unveröffentlicht
  - Design v1: Farben Hintergrund #0B0B0B, Text #F2EBDD, gedämpft #CFC6B6, Linien #2A2826; Überschriften Cormorant, Text Inter; eckige Buttons. Startseite: Hero mit Spruch, Kollektion (3 Spalten), Abschnitt „Die Lilie“.
  - Hinweis: Section-Abstände (padding) dürfen maximal 100 sein.
- **Hochladen ins Live-Theme:** `shopify theme push --store rjydix-2b.myshopify.com --theme 209820844369`
- **Shopify CLI:** liegt in `~/.local/bin/shopify`
- **Vorschau:** `shopify theme dev --store rjydix-2b.myshopify.com` im eigenen Terminal starten (fragt nach dem Shop-Passwort), dann unter http://127.0.0.1:9292
- **Hochladen:** `shopify theme push --store rjydix-2b.myshopify.com` – erst nach Freigabe durch Amin
- Die CLI kann nur das Theme bearbeiten. Produkte, Domains, Zahlungen und Apps laufen über den Shopify-Admin.

## Produkte und Preise (Schätzungen, mit echten Printful-Preisen ersetzen)

| Produkt | Ausführung | Produktion | Verkaufspreis | Marge ca. |
|---|---|---|---|---|
| Beanie | Lilie gestickt, ca. 4 cm hoch | ca. 13–15 € | 27 € | ca. 11 € |
| Longsleeve „Ljiljan“ | Lilie gestickt auf der linken Brust ca. 4 cm hoch (gleiches Motiv wie Beanie), Spruch hinten klein unter dem Kragen als Druck | ca. 22–27 € (Preis prüfen) | ca. 35 € | ca. 7–12 € |
| Longsleeve „Ranke“ | Stickerei vorne mittig ca. 20 × 5–6 cm (Ranke), Spruch hinten klein unter dem Kragen als Druck (ca. 10–12 × 3 cm, 4–5 cm unter der Kragennaht), schwerer Stoff ab ca. 200 g/m² | ca. 27–33 € (größere Stickerei, Preis prüfen) | 39–42 € | ca. 9–13 € |

- **Produktion:** Printful mit EU-Produktion (Qualität und Stickerei wichtiger als ein paar Euro Marge)
- **Steuern:** Kleinunternehmer-Regel (§ 19 UStG)
- **Später, falls es läuft:** Crewneck-Sweatshirt mit großer Stickerei (Mockup-Look), Tasse, Poster, Jutebeutel. Ärmel-Stickerei erst als Premium-Variante.

## Maße und Regeln für Stickerei

- Linien mindestens 1,5–2 mm, Details mindestens 3–4 mm, Abstände mindestens 1–1,5 mm
- Schrift: Großbuchstaben mindestens 7 mm (Rückenschrift gestickt mindestens 9–10 mm), keine haarfeinen Serifen
- 1–2 Garnfarben, keine Verläufe
- Dateien: PNG mit transparentem Hintergrund, 300 DPI in Originalgröße, für Stickerei am besten Vektor (SVG/PDF)
- Fleur-de-Lis durch die **bosnische Lilie** ersetzen (rundere, breitere Blütenblätter)

## Marketing

- **TikTok**, 3–4 Videos pro Woche, KI-Videos im Retro/VHS-Stil im Wechsel mit echten Handy-Clips
- **Videos:** Kling, zuerst über fal.ai (ca. 20 € Test), danach günstiges Kling-Abo. Schnitt in CapCut.
- KI-Videos auf TikTok immer als KI-generiert kennzeichnen, keine erfundenen Kundenstimmen

---

## Checkliste

### ✅ Erledigt
- [x] Shopify-Konto angelegt, 3 Monate für 1 €
- [x] Shopify CLI installiert und mit dem Shop verbunden
- [x] Theme Horizon lokal heruntergeladen und in Git gesichert
- [x] Produkte, Anbieter und Videotool festgelegt
- [x] Domains geprüft (reine „bih“-Domains vergeben oder Premium; bihtime.com, bihatelier.com, verybosnian.com frei)
- [x] CLAUDE.md mit Checkliste angelegt

### 1. Name und Marke (bis 31.10.)
- [x] Markennamen festlegen: bihtime
- [x] Im Markenregister TMview prüfen, ob „bihtime“ geschützt ist (30.10.2026: keine Treffer für „bihtime“, bei „bih time“ nur unpassende Treffer)
- [ ] Optional, niedrige Priorität: prüfen, ob @bihtime auf TikTok und Instagram frei ist
- [x] Domain bihtime.com kaufen (30.10.2026, als Hauptdomain gesetzt, E-Mail verifiziert)
- [ ] Shopnamen von „Mein Shop 2“ auf „bihtime“ ändern (Einstellungen → Allgemein)
- [ ] TikTok- und Instagram-Account anlegen

### 2. Design (bis 31.10.)
- [x] Fleur-de-Lis durch die bosnische Lilie ersetzen
- [x] Beanie-Motiv erstellen (= `design/lilie-final.png`)
- [x] Mockup Longsleeve „Ranke“ (`design/mockup-longsleeve-v1.png`)
- [ ] Mockup mit kleiner Rückenschrift unter dem Kragen aktualisieren
- [x] Produktionsdateien v2 (30.10.2026): `design/ranke-v2.png`, `design/lilie-v2.png`, `design/rueckenschrift-v2.png` – bereinigt (Rauschen entfernt, einheitlich #F2EBDD, 300 DPI), überall dieselbe Lilie aus lilie-v1. Die v1-Dateien sind die ungeänderten Originale aus ChatGPT.
- [x] Motive für Stickerei vereinfachen (dickere Linien, weniger Blätter, keine Schattierung)

### 3. Printful und Teststich (bis ca. 2.11.)
- [x] Printful-Konto anlegen bzw. einloggen
- [ ] Gratis-T-Shirt aus der Mail mitnehmen
- [ ] Beanie und Longsleeve mit Stickerei und EU-Produktion heraussuchen
- [ ] Pro Produkt prüfen: welche Platzierungen (vorne, hinten, Ärmel), ist Stickerei mit Druck kombinierbar?
- [ ] Echte Preise notieren (inkl. Aufpreis pro Platzierung und Digitalisierungsgebühr) und Marge neu rechnen
- [x] Printful-App in Shopify installieren
- [x] Designs hochladen und in Shopify einbinden (erste Produkte über Printful angelegt)
- [ ] Stickvorschau im Designer prüfen
- [ ] Teststich bzw. Muster bestellen (Beanie und Longsleeve mit allen geplanten Platzierungen)
- [ ] Teststich prüfen: feine Linien sauber? Rückenschrift lesbar? Farbe Creme auf Schwarz passend? Stoff zieht sich nicht zusammen, innen nicht kratzig? Stoff und Passform gut?
- [ ] Falls nötig: Motiv vereinfachen und zweiten Teststich bestellen (1–2 Wochen Puffer)

### 4. Formalitäten (bis ca. 5.11.)
- [ ] Gewerbe anmelden (online, Berlin, ca. 15–30 €)
- [ ] Kleinunternehmer-Regel wählen
- [ ] Dienst für Rechtstexte abschließen (z. B. IT-Recht Kanzlei)
- [ ] Prüfen, ob die Registrierung im Verpackungsregister LUCID nötig ist

### 5. Shop (bis ca. 12.11.)
- [x] Claude: Farben, Schriften und Startseite im Theme Horizon einrichten (Entwurf „bihtime Design v1“, 30.10.2026)
- [ ] Claude: Produkttexte und Größentabelle schreiben
- [ ] Amin: alles in der Vorschau prüfen
- [ ] Rechtstexte einbinden (Impressum, Datenschutz, AGB, Widerruf), Cookie-Banner einrichten
- [ ] Shopify Payments und PayPal einrichten
- [ ] Versandzonen und -preise festlegen
- [x] Domain mit dem Shop verbinden

### 6. Videos (parallel)
- [ ] fal.ai-Konto anlegen, ca. 20 € Guthaben aufladen
- [ ] Claude: Skript für Kling bauen und Prompts schreiben
- [ ] Festes Referenzbild der Figur erstellen
- [ ] 2–3 Testvideos: bleibt die Figur gleich, stimmt die Stickerei, klingt das Bosnisch natürlich?
- [ ] Erste Teaser auf TikTok posten („Coming soon“, Warteliste)

### 7. Wenn die Muster da sind (ca. 10.–14.11.)
- [ ] Qualität prüfen
- [ ] Echte Fotos und Clips machen (Vorderseite, Rückseite, Nahaufnahmen, Unboxing)
- [ ] Claude: Fotos in den Shop einbauen
- [ ] Testbestellung durchspielen

### 8. Livegang (ca. 15.–20.11.)
- [ ] Passwort-Schutz des Shops entfernen
- [ ] 3–4 TikToks pro Woche, KI-Videos und echte Clips im Wechsel
- [ ] KI-Videos immer als KI-generiert kennzeichnen

### 9. Termine
- [ ] ca. 10.–15.12.2026: letzte Bestellfrist bei Printful für Weihnachten
- [ ] ca. 20.12.2026: Zwischenbilanz – weitermachen, wenn mindestens eins zutrifft: ein Video über 10.000 Aufrufe, mindestens 10 Verkäufe, mindestens 50 Interessenten
- [ ] 20.01.2027: Entscheidung über das Shopify-Abo (genaues Testende unter Einstellungen → Plan prüfen)
- [ ] bis ca. 29.01.2027: gegebenenfalls kündigen
