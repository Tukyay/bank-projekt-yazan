# Hands-on Exercise Session 3: From CSV to HTML

Dieses Repository enthält das vollständige, abgabebereite Projekt für Session 3. Das Ziel war die schrittweise Weiterentwicklung einer Bankdaten-CSV hin zu einer visuell ansprechenden HTML-Dashboard-Anwendung mithilfe von KI-Assistenz in VS Code.

---

## 👨‍💻 Autor & Lizenz
* **Autor:** Max Mustermann
* **Kurs / Modul:** Hands-on AI Session 3
* **Lizenz:** MIT License

---

## 📊 Datenstruktur (`bank.csv`)
Die ursprüngliche CSV-Datei wurde mit aussagekräftigen, deutschen Spaltenüberschriften versehen und um eine Klassifizierungsspalte erweitert.

### Spaltenübersicht:
1. `Datum`: Datum der Transaktion im Format `YYYY-MM-DD`
2. `Beschreibung`: Verwendungszweck bzw. Name der Gegenpartei
3. `Betrag_EUR`: Betrag in Euro (positiv = Eingang, negativ = Ausgang)
4. `Typ`: Transaktionstyp (`Eingang` / `Ausgang`)
5. `Kategorie`: Automatisch zugewiesene Kategorie (siehe unten)

### Transaktions-Kategorien (5 Klassen):
* **`Geldeingang`**: Gehälter, Boni und Rückzahlungen
* **`Essen, Trinken, Miete`**: Fixkosten, Supermärkte, Gastronomie und Bäckereien
* **`Unterhaltung`**: Streaming-Dienste, Gaming und Abonnements
* **`Freizeit`**: Sportkurse, Kultur- und Freizeitveranstaltungen
* **`Anderes`**: Sonstige Ausgaben, Apotheke, private Zahlungen

---

## 🌐 HTML Dashboard & CSS
Das Projekt trennt Inhalt und Design sauber voneinander (Best Practice):

* **`index.html`**: Enthält die semantische HTML-Struktur der Transaktionstabelle sowie eine KPI-Übersicht für Gesamteinnahmen, Ausgaben und Saldo.
* **`style.css`**: Enthält das vollständige Layout-Styling, inklusive responsiver Tabellenansicht, Hover-Effekten und farblicher Kennzeichnung der Kategorien und Beträge.

---

## 🛠️ Verwendung in VS Code
1. Öffne den Projektordner in VS Code.
2. Öffne `index.html` in einem Browser deiner Wahl (z.B. über die VS Code Live Server Extension oder per Doppelklick in VS Code).