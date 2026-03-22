---
name: frontend-design-agency
description: Use when building, redesigning, or extending web-app frontends that must look production-ready, visually distinctive, and systemically designed instead of like generic AI-generated UI
---

# Frontend Design Agency

## Skill-Name

`frontend-design-agency`

## Kurzbeschreibung

Entwickelt Web-App-Frontends auf Agentur-Niveau.
Der Skill erzwingt Produktverständnis, visuelle Richtung, Designsystem-Logik, hochwertige Referenzrecherche und saubere Frontend-Implementierung.
Er verhindert generische KI-Optik und verlangt vor jeder Umsetzung eine klare gestalterische These.

## Einsatzbereich

Verwende diesen Skill für:
- komplette Seiten
- App-Shells
- Dashboards
- Landingpages
- Form-Flows
- Settings-Bereiche
- Onboarding
- Tabellen- und Listenansichten
- Detailansichten
- Admin-Oberflächen
- mobile-first oder responsive Web-Oberflächen

Verwende ihn besonders, wenn:
- die Oberfläche marktreif und hochwertig wirken soll
- eine erkennbare Produktidentität nötig ist
- ein Interface aktuell zu generisch, technisch oder austauschbar wirkt
- Design und Code als zusammenhängendes System gebaut werden sollen

## Eingaben

Erwarte und extrahiere, soweit vorhanden:
- Produkttyp
- Ziel der Oberfläche
- primäre Nutzerrolle
- Hauptaufgaben der Nutzer
- Markenrahmen oder visuelle Vorgaben
- Inhalte, Datenarten und Informationsdichte
- notwendige Ansichten oder Komponenten
- technischer Stack
- bestehende UI-Bibliotheken oder Designsysteme
- Anforderungen an Accessibility, Responsiveness und Performance

Wenn Angaben fehlen:
1. triff belastbare Annahmen
2. dokumentiere sie knapp
3. entscheide passend zum Produktkontext statt neutral

## Verhaltensregeln

1. Baue niemals einfach direkt eine UI.
2. Verstehe vor jeder Umsetzung:
   - Produkttyp
   - Nutzerrolle
   - Nutzungsszenario
   - primäre Nutzeraufgabe
   - Informationspriorität
   - wichtigste Aktion oder Conversion
3. Definiere vor dem Coden immer eine visuelle Richtung.
4. Arbeite mit einer klaren gestalterischen These, nicht mit beliebigen Komponenten.
5. Begründe die zentrale Stilentscheidung knapp und konkret.
6. Reduziere Komplexität sichtbar durch Hierarchie, Gruppierung und Führung.
7. Liefere kein loses Set schöner Blöcke, sondern ein zusammenhängendes Produktsystem.
8. Verbessere generische Entwürfe aktiv, bevor du sie ausgibst.
9. Denke Desktop und Mobile zusammen.
10. Implementiere nur Lösungen, deren visuelle und funktionale Logik du benennen kannst.

## Research-Regeln

Wenn Webzugriff verfügbar ist:
1. recherchiere gezielt 3 bis 5 hochwertige Referenzen
2. suche nach:
   - passenden Produktmustern
   - Layout-Systemen
   - Navigationsmustern
   - Formular- und Tabellenmustern
   - Detailansichten
   - Datenvisualisierungsmustern
   - Icon-Systemen
   - Typografie-Ansätzen
3. bevorzuge hochwertige Quellen:
   - reale SaaS-Produkte
   - etablierte Produktseiten
   - Designsysteme
   - hochwertige Showcase-Quellen mit erkennbarer Produktqualität
4. leite aus den Referenzen konkrete Prinzipien ab
5. kopiere nie 1:1
6. dokumentiere kurz:
   - welche Richtung übernommen wird
   - welche Elemente bewusst nicht übernommen werden
   - welche eigenständige Designsprache daraus entsteht

Wenn kein Webzugriff verfügbar ist:
1. arbeite mit aktuellen, hochwertigen Produktmustern
2. definiere die angenommene Stilrichtung trotzdem explizit
3. rate nicht planlos, sondern entscheide bewusst entlang des Produkttyps

Nutze die Referenzdateien:

**Workflow & Planung:**
- `references/research-workflow.md` - Recherche-Strategie
- `references/visual-direction-canvas.md` - Gestalterische These
- `references/design-system-rules.md` - System-Regeln
- `references/quality-gate.md` - Qualitätsprüfung

**Design System Assets:**
- `references/color-palette-examples.md` - Fertige Farbpaletten
- `references/typography-scale-template.md` - Typografie-System
- `references/motion-system-guide.md` - Animation & Timing
- `references/component-template.tsx` - React/Tailwind Templates
- `references/breakpoint-definition.md` - Responsive Design
- `references/accessibility-checklist.md` - WCAG 2.1 AA
- `references/user-persona-template.md` - Nutzer-Definition
- `references/product-requirements-checklist.md` - Anforderungen
- `references/grid-system-template.md` - 12-Spalten Grid
- `references/layout-patterns-library.md` - Layout-Patterns
- `references/focus-states-template.md` - Focus-Indikatoren
- `references/generic-vs-distinctive-examples.md` - Vorher/Nachher

## Design-Regeln

### 1. Kein KI-Einheitsbrei

Vermeide:
- austauschbare Kartenraster ohne Priorisierung
- generische Dashboard-Kompositionen
- übermäßige Gradients
- dekorative Glows ohne funktionalen Zweck
- sterile Standard-Blöcke
- visuelle Identität ohne These
- zufällige Accent-Farben
- überladene Badges, Pills und Schatten
- UI, die nur aus Default-Komponenten zusammengesetzt wirkt

### 2. Visuelle Richtung zuerst

Definiere vor jeder Umsetzung:
- Stilrichtung
- visuelle Referenzen
- Farbkonzept
- Typografie-Hierarchie
- Icon-Stil
- Spacing-System
- Radius-Logik
- Border-Logik
- Shadow-Logik
- Motion-Prinzipien

### 3. Produktdesign statt Deko

Die Oberfläche muss:
- Prioritäten sofort sichtbar machen
- wichtige Aktionen dominant führen
- sekundäre Informationen sauber staffeln
- dichte Informationen lesbar halten
- Orientierung ohne unnötige Deko verbessern
- eine glaubwürdige Produktästhetik aufbauen

### 4. Systemisches UI

Arbeite immer mit:
- Design Tokens
- Farbrollen statt Einzelwerten
- Typo-Skalen
- Spacing-Skalen
- konsistenten Oberflächenregeln
- wiederverwendbaren Komponenten
- Zuständen für Hover, Focus, Active, Disabled, Error, Empty, Loading
- responsivem Verhalten mit klaren Breakpoint-Entscheidungen

### 5. Gestalterische These

Jede UI braucht genau eine klar benennbare Hauptthese, zum Beispiel:
- editorial und präzise
- ruhig und datenfokussiert
- premium und reduziert
- technisch, dicht und kontrolliert
- warm, serviceorientiert und vertrauensstark

Definiere die Hauptthese und halte sie über Layout, Typografie, Farbe, Komponenten und Motion konsistent.

### 6. Typografie und Raum

Bevorzuge:
- starke visuelle Hierarchie
- hochwertige Weißraum-Nutzung
- wenige, präzise Akzente
- klare Leselinien
- glaubwürdige SaaS- oder Produktästhetik
- differenzierte Flächen statt Kartenfriedhof

## Tech-Regeln

Bevorzugter Stack:
- Next.js
- React
- TypeScript
- Tailwind CSS
- shadcn/ui

Icon-Regeln:
- `lucide-react` nur verwenden, wenn es stilistisch passt
- sonst aktiv hochwertigere Alternativen prüfen, wenn verfügbar
- mische nicht mehrere Icon-Stile ohne Begründung

Code-Regeln:
- modular
- lesbar
- wiederverwendbar
- produktionsnah
- barrierearm
- responsive
- ohne unnötigen Ballast

Implementierungsregeln:
1. verwende semantische HTML-Struktur
2. beachte Tastaturbedienbarkeit und Fokuszustände
3. definiere Tokens oder CSS-Variablen für zentrale Stilwerte
4. extrahiere wiederkehrende Muster in Komponenten
5. nutze Tailwind systemisch statt chaotisch
6. passe shadcn/ui-Komponenten sichtbar an die definierte Designsprache an
7. lasse Default-Styling nie unreflektiert stehen

## Ablauf

1. Ziel und Kontext extrahieren.
2. Zielgruppe und Nutzungsszenario ableiten.
3. Primäre Nutzeraufgabe und Informationsprioritäten festlegen.
4. Visuelle Richtung definieren.
5. Web-Recherche durchführen, falls möglich.
6. Designprinzipien aus Referenzen ableiten.
7. Informationsarchitektur festlegen.
8. Komponentenplan erstellen.
9. Design Tokens und Stilregeln definieren.
10. Layoutsystem festlegen.
11. UI implementieren.
12. Interaction States ergänzen.
13. Responsive Verhalten ergänzen.
14. Ergebnis gegen Qualitätskriterien prüfen.
15. Offensichtlich generische Stellen aktiv überarbeiten.
16. Erst dann final ausgeben.

## Qualitätskontrolle

Prüfe vor Abschluss immer:

### Produktqualität

- Wirkt die Oberfläche wie ein reales Produkt statt wie ein Demo-Template?
- Hat die UI eine erkennbare Identität?
- Ist die Hauptaktion klar geführt?
- Sind Informationsdichte und Lesbarkeit ausbalanciert?

### Visuelle Qualität

- Gibt es eine saubere Hierarchie?
- Sind Abstände konsistent?
- Sind Farben rollenbasiert und nachvollziehbar?
- Sind Radius, Border und Shadow systemisch?
- Wirkt die Oberfläche hochwertig, aber nicht dekorativ überladen?

### Systemqualität

- Gibt es wiederverwendbare Komponenten?
- Sind Zustände vollständig abgedeckt?
- Ist das responsive Verhalten konsistent?
- Sind Tokens oder zentrale Stilregeln erkennbar?

### Codequalität

- Ist der Code sauber strukturiert?
- Sind Komponenten sinnvoll geschnitten?
- Ist unnötige Komplexität vermieden?
- Ist die Lösung barrierearm und produktionsnah?

Wenn eine dieser Fragen mit nein beantwortet wird, ist die Arbeit nicht fertig.

## Verbote

Verboten sind:
- generische KI-Optik
- zufällige Farbentscheidungen
- Default-UI ohne Designentscheidung
- Kartenfriedhof ohne Priorisierung
- schlechte Abstände
- unklare visuelle Hierarchie
- überladene Effekte
- rein dekorative Glows
- unmotivierte Gradients
- Desktop-only-Denken
- fehlende Zustände
- Komponenten ohne Systemlogik
- 1:1-Kopien aus Referenzen
- beliebige Icon-Mischung
- rein technische Implementierung ohne Produktlogik

## Definition of Done

Der Task ist erst abgeschlossen, wenn:
1. Produkttyp, Nutzerrolle und Nutzungsszenario klar benannt wurden.
2. Eine visuelle Richtung explizit definiert wurde.
3. Referenzen recherchiert oder eine belastbare Stilannahme dokumentiert wurden.
4. Informationsarchitektur und Komponentenplan festgelegt wurden.
5. Design Tokens oder klare Stilregeln erkennbar sind.
6. Die UI eine klare gestalterische These hat.
7. Alle relevanten Zustände ergänzt wurden.
8. Die Oberfläche responsive und barrierearm ist.
9. Der Code modular und produktionsnah ist.
10. Das Ergebnis nicht wie generische KI-UI wirkt.

## Beispiel-Prompt zur Nutzung des Skills

Nutze `frontend-design-agency`, um eine B2B-SaaS-Oberfläche für ein Incident-Management-Produkt zu entwerfen und in Next.js mit TypeScript, Tailwind und shadcn/ui umzusetzen. Recherchiere visuelle Referenzen, definiere zuerst eine klare Designrichtung, leite daraus Tokens und Komponentenregeln ab und baue anschließend eine hochwertige, responsive App-Shell mit Dashboard, Vorfallsliste und Detailansicht. Vermeide generische KI-Dashboard-Optik und begründe die gestalterische These kurz vor der Implementierung.
