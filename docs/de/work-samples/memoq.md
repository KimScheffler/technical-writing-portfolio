# memoQ (Version 9.7.12)

## Inhalt

1. [Was ist memoQ?](#was-ist-memoq)
2. [Was ist ein memoQ-Projekt?](#was-ist-ein-memoq-projekt)
3. [Ein neues memoQ-Projekt erstellen](#ein-neues-memoq-projekt-erstellen)
4. [Eine Excel-Datei zur Übersetzung hinzufügen](#eine-excel-datei-zur-übersetzung-hinzufügen)
5. [Was ist ein Translation Memory?](#was-ist-ein-translation-memory)
6. [Ein Translation Memory hochladen](#ein-translation-memory-hochladen)
7. [Was ist eine Term Base (Glossar)?](#was-ist-eine-term-base-glossar)
8. [Eine Term Base (Glossar) hochladen](#eine-term-base-glossar-hochladen)
9. [Während der Übersetzung einen neuen Term zur Term Base hinzufügen](#während-der-übersetzung-einen-neuen-term-zur-term-base-hinzufügen)
10. [Eine übersetzte Datei exportieren](#eine-übersetzte-datei-exportieren)
11. [Referenzmaterial](#referenzmaterial)
    - [Benutzeroberflächenbereiche in memoQ](#benutzeroberflächenbereiche-in-memoq)
    - [Tastenkombinationen (Auswahl)](#tastenkombinationen-auswahl)

---

## Was ist memoQ?

**memoQ** ist eine professionelle Übersetzungsumgebung, die von Übersetzern,
Reviewern und Lokalisierungsteams zur Durchführung und Verwaltung von
Übersetzungsprojekten verwendet wird.

Die Software unterstützt die Übersetzung mehrsprachiger Inhalte durch die
Kombination von Quelldateien mit linguistischen Ressourcen wie
**Translation Memories** und **Term Bases (Glossare)**.

memoQ wird in professionellen Übersetzungsworkflows eingesetzt, um
Konsistenz, Qualität und Effizienz über Projekte hinweg sicherzustellen.

![memoQ – Startansicht](../../assets/images/memoq-start.png)

---

## Was ist ein memoQ-Projekt?

Ein **memoQ-Projekt** ist der zentrale Arbeitsbereich, in dem alle
übersetzungsrelevanten Dateien und Ressourcen verwaltet werden.

Ein Projekt definiert die Quell- und Zielsprachen, enthält die zu übersetzenden
Dateien und dient als Container für Übersetzungsressourcen wie
**Translation Memories (TMs)** und **Glossare (Term Bases)**.

Alle weiteren Arbeitsschritte in memoQ – etwa das Zuweisen von TMs,
das Hinzufügen von Glossaren oder das Starten der Übersetzung –
erfolgen immer im Kontext eines bestehenden Projekts.

---

## Ein neues memoQ-Projekt erstellen

Erstellen Sie ein neues memoQ-Projekt als Grundlage für die Verwaltung von
Übersetzungsdateien und linguistischen Ressourcen.

1. Öffnen Sie **memoQ**.
2. Wählen Sie im **Dashboard** die Option **New project**.
   ![Neues Projekt in memoQ erstellen](../../assets/images/memoq-new-project.png)
3. Geben Sie einen **Projektnamen** ein, der den Übersetzungsauftrag eindeutig beschreibt.
   ![Neues memoQ-Projekt – Projektnamen und Sprachauswahl](../../assets/images/memoq-new-project-2.png)
4. Wählen Sie die erforderliche **Source language** (Quellsprache) und **Target language** (Zielsprache) aus.
5. Klicken Sie auf **Next**, um im Projektassistenten fortzufahren.
6. Fügen Sie bei Bedarf die zu übersetzenden Dateien hinzu.
7. Klicken Sie auf **Finish**, um das Projekt zu erstellen.

Das memoQ-Projekt wird erstellt und ist bereit, mit
**Translation Memories** und **Glossaren** ergänzt zu werden.

---

## Eine Excel-Datei zur Übersetzung hinzufügen

Dieser Task beschreibt, wie eine Excel-Datei mithilfe von Importoptionen
in ein memoQ-Projekt importiert wird, sodass die richtigen Spalten für die
Übersetzung vorbereitet sind.

### Voraussetzungen
- Ein memoQ-Projekt ist erstellt und geöffnet.
- Die Struktur der Excel-Datei (Quell- und Zielspalten) ist bekannt.

### Schritte

1. Wählen Sie **Translations** in der Projektnavigation aus.
   ![Bereich „Translations“ in memoQ](../../assets/images/memoq-translations.png)
2. Wählen Sie **Import with options**.
3. Wählen Sie die Excel-Datei aus und klicken Sie auf **Open**.
4. Klicken Sie auf **Change filter and configuration**.
5. Konfigurieren Sie die Importoptionen:
   - Wählen Sie als **Filter** den **Multilingual delimited text filter**.
   - Aktivieren Sie **Simple bilingual configuration**.
   - Legen Sie **Source** (Spalte der Quellsprache) und **Target** (Spalte der Zielsprache) fest (z. B. Spalten A und B).
   - Aktivieren Sie **First row contains column names**, falls zutreffend.
   ![Importeinstellungen für Dokumente](../../assets/images/memoq-import-settings.png)
6. Klicken Sie auf **OK** und anschließend erneut auf **OK**, um den Import abzuschließen.

Die Excel-Datei wird in das memoQ-Projekt importiert und mit korrekt zugewiesenen
Quell- und Zielspalten für die Übersetzung vorbereitet.

---

## Was ist ein Translation Memory?

Ein **Translation Memory (TM)** ist eine Datenbank, in der bereits übersetzte
Textsegmente als Quell–Ziel-Paare gespeichert werden.

Während der Übersetzung vergleicht memoQ neue Inhalte mit vorhandenen Einträgen
im Translation Memory und schlägt passende Übersetzungen vor, z. B.:

- exakte Übereinstimmungen
- ähnliche (fuzzy) Übereinstimmungen

Der Einsatz eines Translation Memorys hilft dabei:

- effizienter zu arbeiten
- Konsistenz über Projekte hinweg sicherzustellen
- vorhandene Übersetzungen für wiederkehrende Inhalte zu nutzen

Translation Memories werden in der Regel in ein Projekt importiert und dem
jeweiligen Sprachpaar zugewiesen.

---

## Ein Translation Memory hochladen

So wird ein vorhandenes Translation Memory (TM) zu einem memoQ-Projekt hinzugefügt, um bereits übersetzte Inhalte während der Übersetzung wiederzuverwenden.

### Voraussetzungen
- Ein memoQ-Projekt ist erstellt und geöffnet.
- Eine Translation-Memory-Datei ist verfügbar (z. B. eine `.tmx`-Datei).

### Schritte

1. Wählen Sie **Translation memories** in der Projektnavigation aus.
   ![Bereich „Translation memories“ in memoQ](../../assets/images/memoq-new-TM.png)
2. Klicken Sie mit der rechten Maustaste in die TM-Liste und wählen Sie **Create/Use New**.
3. Geben Sie einen Namen ein, der zum Projekt passt.
4. Klicken Sie mit der rechten Maustaste auf den neuen Eintrag und wählen Sie **Import TM**.
5. Navigieren Sie zum Speicherort der Translation-Memory-Datei, wählen Sie sie aus und bestätigen Sie.
6. Überprüfen Sie in den **Translation memory TMX import settings** die **Source** (Quellsprache) und **Target** (Zielsprachen) und passen Sie die Importoptionen bei Bedarf an.
   ![TMX-Importeinstellungen für Translation Memories](../../assets/images/memoq-TM-settings.png)
7. Klicken Sie auf **OK**, um den Import abzuschließen.

Das Translation Memory wird dem Projekt hinzugefügt und kann während der Übersetzung automatisch vorhandene Übersetzungen vorschlagen.

---

## Was ist eine Term Base (Glossar)?

Eine **Term Base** (auch Glossar genannt) speichert **freigegebene Terminologie**
und deren Übersetzungen.

Im Gegensatz zu einem Translation Memory enthält eine Term Base einzelne Terme
und keine vollständigen Sätze. Während der Übersetzung hebt memoQ Terme aus der
Term Base hervor, um eine korrekte und konsistente Terminologieverwendung zu unterstützen.

**Term Bases werden häufig eingesetzt, um:**

- bevorzugte Terminologie durchzusetzen
- Konsistenz in technischen oder regulierten Inhalten sicherzustellen
- falsche oder veraltete Terme zu vermeiden

Term Bases werden in der Regel in ein Projekt importiert und den relevanten
Sprachen zugewiesen.

---

## Eine Term Base (Glossar) aus einer Excel-Datei hochladen

### Voraussetzungen
- Ein memoQ-Projekt ist erstellt und geöffnet.
- Eine Term-Base-Datei liegt als Excel-Datei mit Quell- und Zielspalten vor.

### Schritte

1. Wählen Sie **Term bases** in der Projektnavigation aus.
   ![Bereich „Term bases“ in memoQ](../../assets/images/memoq-new-TB.png)
2. Klicken Sie mit der rechten Maustaste in die Term-Base-Liste und wählen Sie **Create/Use New**.
3. Geben Sie einen Namen ein, der zum Projekt passt.
4. Klicken Sie mit der rechten Maustaste auf den neuen Eintrag und wählen Sie **Import term base**.
5. Navigieren Sie zum Speicherort der Term-Base-Datei, wählen Sie sie aus und bestätigen Sie.
6. Überprüfen Sie, ob die **Importeinstellungen für die Term Base** und Sprachspalten korrekt zugeordnet sind.
   ![Importeinstellungen für Term Base aus Excel](../../assets/images/memoq-TB-language.png)
7. Klicken Sie auf **OK**, um den Import abzuschließen.

Die Term Base wird dem Projekt hinzugefügt und freigegebene Terminologie
wird während der Übersetzung hervorgehoben.

---

## Während der Übersetzung einen neuen Term zur Term Base hinzufügen

Dieser Task beschreibt, wie während der Übersetzung ein neuer Term direkt zu einer bestehenden Term Base hinzugefügt wird.

### Voraussetzungen
- Ein Übersetzungsdokument ist geöffnet.
- Eine Term Base ist verfügbar und dem Projekt zugewiesen.

### Schritte

1. Wählen Sie im **Ribbon** den Tab **Translation**.
2. Wählen Sie **Add Term**.
3. Geben Sie den **Quellsprachterm** ein.
4. Geben Sie den entsprechenden **Zielsprachterm** ein.
5. Speichern Sie den neuen Term.

Der neue Term wird der Term Base hinzugefügt und steht für
Termerkennung und Konsistenzprüfungen während der Übersetzung zur Verfügung.

### Hinweise

- Sie können den englischen Term und den entsprechenden deutschen Term im Text markieren und anschließend **Quick Add Term** wählen, um den Term ohne Öffnen des Assistenten hinzuzufügen.
- Alternativ können Sie einen Term auch über eine Tastenkombination hinzufügen. Weitere Informationen finden Sie unter [*Tastenkombinationen*](#tastenkombinationen-auswahl).

---

## Eine übersetzte Datei exportieren

### Voraussetzungen
- Das übersetzte Dokument ist fertig und kann geliefert werden.
- Alle QA-Prüfungen sind abgeschlossen (z. B. keine fehlenden Tags oder Formatierungsfehler).

### Schritte

1. Wählen Sie **Documents** in der Projektnavigation aus.
   ![Datei in memoQ exportieren](../../assets/images/memoq-export.png)
2. Wählen Sie im Menü **Export**.
3. Wählen Sie **Export (Choose path)**.
4. Wählen Sie den Zielordner für die exportierte Datei aus.
5. Bestätigen Sie den Export.

Die übersetzte Datei wird am ausgewählten Speicherort abgelegt und kann
in das Projektsystem hochgeladen oder als Ersatz für die Originaldatei verwendet werden.

---

## Referenzmaterial

### Benutzeroberflächenbereiche in memoQ

- **Dashboard** – Startansicht zum Erstellen und Öffnen von Projekten.
- **Projektnavigation** – Linker Navigationsbereich innerhalb eines memoQ-Projekts.
- **Ribbon** – Oberer Menübereich mit Tabs und Befehlen.
- **Übersetzungseditor** – Zentraler Bereich zum Übersetzen und Prüfen von Segmenten.

---

### Tastenkombinationen (Auswahl)

Die folgenden Tastenkombinationen werden häufig bei Übersetzung und Review
in memoQ verwendet:

- **Strg + Enter** – Segment bestätigen
- **Strg + Umschalt + Enter** – Segment bestätigen und zum nächsten wechseln
- **Strg + Z** – Letzte Aktion rückgängig machen
- **Strg + C / Strg + V** – Inhalt kopieren / einfügen
- **Strg + F** – Im Dokument suchen
- **Strg + E** – Neuen Terminus hinzufügen *(entspricht **Translation > Add Term**)*


