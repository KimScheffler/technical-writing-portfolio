# Styleguide – Deutsche Software-Dokumentation

Dieser Styleguide definiert verbindliche Richtlinien für die Erstellung
deutscher, **aufgabenorientierter Software-Dokumentation** in diesem Portfolio.
Er gilt projektübergreifend (z. B. für das Snipping Tool und memoQ).

---

## Inhalt

1. [Informationsarten](#informationsarten)
2. [Sprachstil](#sprachstil)
3. [Satzbau und Stil](#satzbau-und-stil)
4. [Terminologie](#terminologie)
5. [Struktur von Tasks](#struktur-von-tasks)
6. [Hinweise](#hinweise)
7. [Referenzinformationen](#referenzinformationen)
8. [Bilder und Grafiken](#bilder-und-grafiken)
9. [Barrierefreiheit](#barrierefreiheit)
10. [Wartbarkeit](#wartbarkeit)

## Informationsarten

Es wird konsequent zwischen folgenden Informationstypen unterschieden:

- **Concept**  
  Erklärt, *was* etwas ist und *wofür* es verwendet wird.
- **Task**  
  Beschreibt Schritt für Schritt, *wie* ein Ziel erreicht wird.
- **Reference**  
  Liefert nachschlagbare Informationen (z. B. Formate, Optionen, Tastenkombinationen).

Informationstypen werden **nicht vermischt**.

---

## Sprachstil

### Tonalität
- sachlich
- neutral
- hilfreich
- nicht werbend

### Anrede
- **Sie-Form** wird durchgängig verwendet.

### Aktiv statt Passiv
- ✔ *Klicken Sie auf **Neu***  
- ✘ *Der Button **Neu** wird angeklickt*

### Sprachvariante

### Sprachvariante

Die deutsche Dokumentation wird in **Standarddeutsch** verfasst.

Die Sprache von **UI-Elementen (z. B. Bedienfelder, Schaltflächen, Modi)** wird
exakt so übernommen, wie sie in der jeweiligen Benutzeroberfläche angezeigt wird.
Ist dies für das Verständnis erforderlich, kann eine **deutsche Übersetzung in Klammern**
ergänzend angegeben werden.


### Geschlechtergerechte Sprache

In dieser Dokumentation wird aus Gründen der besseren Lesbarkeit
das **generische Maskulinum** verwendet. Die verwendeten Personenbezeichnungen beziehen sich gleichermaßen
auf alle Geschlechter.

Diese Entscheidung dient der sprachlichen Klarheit und Konsistenz und stellt keine Wertung dar.

---

## Satzbau und Stil

### Kurz und klar
- Ein Gedanke pro Satz
- Vermeidung von Schachtelsätzen

### Imperativ in Tasks
- Jeder Schritt beginnt mit einem Verb im Imperativ:
  - *Öffnen Sie …*
  - *Wählen Sie …*
  - *Klicken Sie …*

### Reihenfolge
- **Aktion → Zweck**
  
> **Beispiel:**  
>*Klicken Sie auf **Neu**, um den Aufnahmemodus zu starten.*

---

## Terminologie

In der Dokumentation werden **UI-Bezeichnungen exakt so verwendet, wie sie in der jeweiligen Benutzeroberfläche angezeigt werden**.

### Konsistenz

UI-Elemente werden:
- **nicht übersetzt**, wenn sie in der Anwendung englisch sind
- **nicht paraphrasiert**
- **einheitlich formatiert** (fett hervorgehoben)
- Ein Begriff = eine Bedeutung

Dies gilt insbesondere für Schaltflächen, Modi und Werkzeugnamen.

Verbindliche UI-Bezeichnungen sind im projektspezifischen Glossar definiert und werden in der Dokumentation konsistent verwendet.

Ist ein technischer Fachbegriff unter einer allgemein gebräuchlicheren Bezeichnung bekannt, wird der technische Fachbegriff als Primärbegriff verwendet und bei der ersten Nennung durch die gebräuchliche Bezeichnung in Klammern ergänzt (z. B. *Term Base (Glossary)*). Der Primärbegriff wird anschließend konsistent verwendet.

---

## Struktur von Tasks

Jeder Task besteht aus:

1. **Überschrift** (Ziel des Tasks)
2. **Schritte** + **Ergebnis** (Outcome)

#### Optional:
- **Hinweise** für Optionen oder Sonderfälle
- **keine** Feature-Listen in Tasks

### Listen und Schrittfolgen

In der Dokumentation werden unterschiedliche Listentypen gezielt eingesetzt:

- **Nummerierte Listen** werden verwendet, wenn die **Reihenfolge der Schritte relevant** ist,
  insbesondere bei Anleitungen und Tasks.
- **Aufzählungen (Bulletpoints)** werden verwendet, wenn die **Reihenfolge keine Rolle spielt**,
  z. B. bei Optionen, Hinweisen oder Referenzinformationen.

#### Umfang von Schrittfolgen

Eine Schrittfolge sollte **nicht mehr als 10 Schritte** enthalten.

Wenn ein Ablauf mehr als 10 Schritte erfordert:
- wird der Task in **zwei oder mehr logisch abgegrenzte Tasks** aufgeteilt  
  **oder**
- der Ablauf wird durch eine **übersichtliche Grafik oder Prozessdarstellung** ergänzt.

Ziel ist es, komplexe Abläufe übersichtlich, verständlich und gut wartbar zu halten.

#### Unterpunkte (Substeps) in Schrittfolgen

Unterpunkte dürfen innerhalb eines nummerierten Schritts verwendet werden,
wenn sie konfigurierende oder erläuternde Teilschritte beschreiben, die
funktional zu einem Hauptschritt gehören.

**Unterpunkte dürfen verwendet werden, wenn:**  
- sie keine eigenständige Aktion darstellen
- sie nicht sinnvoll allein nummeriert werden können
- sie Optionen, Einstellungen oder Parameter konkretisieren

**Unterpunkte dürfen nicht verwendet werden, um:**  
- eigenständige Hauptaktionen zu verstecken
- die 10-Schritte-Regel zu umgehen

Wenn mehrere Unterpunkte jeweils eigenständige Aktionen beschreiben,
muss der Task in separate Schritte oder einen eigenen Task aufgeteilt werden.

---

## Hinweise

Tasks können **kurze Hinweise** enthalten, die auf relevante
**Referenzabschnitte** verlinken (z. B. Tastenkombinationen oder UI-Übersichten).

Dabei gelten folgende Regeln:
- Hinweise sind optional
- Hinweise stehen **nach** den Schritten
- Hinweise beschreiben Optionen oder ergänzende Informationen
- Hinweise enthalten **keine** Schrittfolgen
- Hinweise verlinken auf Referenzabschnitte

Dieser Ansatz hält Tasks schlank und übersichtlich und stellt gleichzeitig sicher,
dass zusätzliche Informationen zentral und gut wartbar bleiben.

> **Beispiele:**  
> - *Sie können diese Aktion auch über eine Tastenkombination ausführen. Weitere Informationen finden Sie unter Tastenkombinationen.*  
> - *Beim Kopieren von Text können Sie optional Zeilenumbrüche automatisch entfernen.*


---

## Referenzinformationen

Referenzinformationen:
- sind nachschlagbar
- enthalten keine vollständigen Tasks
- dürfen Tabellen oder Listen enthalten

Geeignet für:
- Tastenkombinationen
- Dateiformate
- Einstellungen
- UI-Elemente, die mehrfach verwendet werden

---

## Bilder und Grafiken

### Einsatz
- Nur verwenden, wenn sie einen Mehrwert bieten
- Maximal 1–2 Bilder pro Task
- Keine dekorativen Bilder

### Platzierung
- Direkt nach dem Schritt, auf den sie sich beziehen
- Oder zentral in den Referenzinformationen bei Wiederverwendung

### Alt-Text
- beschreibt **Inhalt und Zweck** des Bildes
- keine generischen Begriffe wie „Screenshot“

> **Beispiel:**  
> *Schaltfläche zur Auswahl des Foto-Modus im Snipping Tool*

### Hervorhebung von UI-Elementen

Zur Hervorhebung von UI-Elementen in Screenshots werden **rechteckige Markierungen** verwendet.

Die Markierungen folgen diesen verbindlichen Vorgaben:
- Form: **Rechteck**
- Farbe: **Standardrot** (RGB **255, 0, 0**)
- Linienstärke: **3 pt**
- Keine Füllung, nur Umrandung

UI-Elemente werden ausschließlich dann hervorgehoben, wenn dies zum Verständnis
eines Arbeitsschritts erforderlich ist. Mehrere UI-Elemente dürfen im selben Screenshot
markiert werden, sofern sie im gleichen Kontext erläutert werden.

Dekorative Markierungen oder unterschiedliche Farben werden nicht verwendet.

---

## Barrierefreiheit

- Aussagekräftige Überschriften
- Sinnvolle Alt-Texte
- Keine rein visuellen Anweisungen („siehe oben“, „wie im Bild“)

---

## Wartbarkeit

- Redundanzen vermeiden
- Wiederverwendbare Informationen zentralisieren
- UI-abhängige Details möglichst abstrahieren
- Änderungen über Software-Releases hinweg erleichtern
