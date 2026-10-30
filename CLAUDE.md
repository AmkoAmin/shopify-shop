# Bosnien-Merch-Shop – Projektkontext und Checkliste

Stand: 29.10.2026. Checkboxen beim Erledigen abhaken (`[x]`) und neue Entscheidungen hier nachtragen.
Technische Hinweise zum Theme stehen in `AGENTS.md`.

## Projekt

- **Idee:** ruhiges, hochwertiges Label für die bosnische Diaspora (16–35, v. a. DE, AT, CH, Skandinavien, USA). Vintage-Stickerei, bosnische Lilie, Nostalgie mit Augenzwinkern.
- **Leitspruch:** „you met me at a very bosnian time in my life“
- **Stil:** Schwarz, Anthrazit, Creme. Serifenschrift für Überschriften, viel Leerraum.
- **Erster Entwurf:** `design/mockup-hoodie-v1.png` (KI-Mockup Hoodie: Ranke mit Lilie vorne, Spruch hinten). Lilie ist dort noch eine französische Fleur-de-Lis, und die Ranke ist für Stickerei zu fein.
- **Markenname:** **bihtime** (entschieden am 29.10.2026). Domain: **bihtime.com** (am 29.10. frei, noch nicht gekauft). Hashtag/Accounts: #bihtime, @bihtime. Variante bih-time.com ebenfalls frei, optional als Weiterleitung.
- **Nicht verwenden:** „Made in BiH“ – Printful produziert nicht in Bosnien, das wäre irreführend.

## Technik

- **Shop:** `rjydix-2b.myshopify.com`, Shopify Basic (3 Monate für 1 €, danach 36 €/Monat)
- **Theme:** Horizon (live, ID 209718837585), lokal in diesem Ordner, Git-Repo mit Ausgangsstand
- **Shopify CLI:** liegt in `~/.local/bin/shopify`
- **Vorschau:** `shopify theme dev --store rjydix-2b.myshopify.com` im eigenen Terminal starten (fragt nach dem Shop-Passwort), dann unter http://127.0.0.1:9292
- **Hochladen:** `shopify theme push --store rjydix-2b.myshopify.com` – erst nach Freigabe durch Amin
- Die CLI kann nur das Theme bearbeiten. Produkte, Domains, Zahlungen und Apps laufen über den Shopify-Admin.

## Produkte und Preise (Schätzungen, mit echten Printful-Preisen ersetzen)

| Produkt | Ausführung | Produktion | Verkaufspreis | Marge ca. |
|---|---|---|---|---|
| Beanie | Lilie gestickt, ca. 4 cm hoch | ca. 13–15 € | 27 € | ca. 11 € |
| Longsleeve | Stickerei linke Brust ca. 10 × 5 cm, Spruch hinten als Druck ca. 24 cm breit | ca. 24–30 € | 39 € | ca. 11–13 € |

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
- [ ] Domain bihtime.com kaufen (Shopify → Einstellungen → Domains, ca. 10–18 €/Jahr)
- [ ] TikTok- und Instagram-Account anlegen

### 2. Design (bis 31.10.)
- [ ] Fleur-de-Lis durch die bosnische Lilie ersetzen
- [ ] Beanie-Motiv erstellen (Lilie ca. 4 cm hoch, eventuell mit Schriftzug)
- [ ] Longsleeve-Motive erstellen: Brust-Stickerei ca. 10 × 5 cm, Rückendruck ca. 24 cm breit
- [ ] Motive für Stickerei vereinfachen (dickere Linien, weniger Blätter, keine Schattierung)

### 3. Printful und Teststich (bis ca. 2.11.)
- [ ] Printful-Konto anlegen bzw. einloggen
- [ ] Gratis-T-Shirt aus der Mail mitnehmen
- [ ] Beanie und Longsleeve mit Stickerei und EU-Produktion heraussuchen
- [ ] Pro Produkt prüfen: welche Platzierungen (vorne, hinten, Ärmel), ist Stickerei mit Druck kombinierbar?
- [ ] Echte Preise notieren (inkl. Aufpreis pro Platzierung und Digitalisierungsgebühr) und Marge neu rechnen
- [ ] Printful-App in Shopify installieren
- [ ] Designs hochladen und die Stickvorschau im Designer prüfen
- [ ] Teststich bzw. Muster bestellen (Beanie und Longsleeve mit allen geplanten Platzierungen)
- [ ] Teststich prüfen: feine Linien sauber? Rückenschrift lesbar? Farbe Creme auf Schwarz passend? Stoff zieht sich nicht zusammen, innen nicht kratzig? Stoff und Passform gut?
- [ ] Falls nötig: Motiv vereinfachen und zweiten Teststich bestellen (1–2 Wochen Puffer)

### 4. Formalitäten (bis ca. 5.11.)
- [ ] Gewerbe anmelden (online, Berlin, ca. 15–30 €)
- [ ] Kleinunternehmer-Regel wählen
- [ ] Dienst für Rechtstexte abschließen (z. B. IT-Recht Kanzlei)
- [ ] Prüfen, ob die Registrierung im Verpackungsregister LUCID nötig ist

### 5. Shop (bis ca. 12.11.)
- [ ] Claude: Farben, Schriften und Startseite im Theme Horizon einrichten
- [ ] Claude: Produkttexte und Größentabelle schreiben
- [ ] Amin: alles in der Vorschau prüfen
- [ ] Rechtstexte einbinden (Impressum, Datenschutz, AGB, Widerruf), Cookie-Banner einrichten
- [ ] Shopify Payments und PayPal einrichten
- [ ] Versandzonen und -preise festlegen
- [ ] Domain mit dem Shop verbinden

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
