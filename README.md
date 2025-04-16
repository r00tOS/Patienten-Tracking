# 🏥 Patienten-Tracking im Sanitätsdienst

## Projektbeschreibung

Diese Webanwendung dient der strukturierten Erfassung, Verfolgung und Verwaltung von Patienten während Sanitätsdiensten, Großveranstaltungen oder Katastropheneinsätzen.

> **Einsatzbereiche:**  
Sanitätsdienste, Katastrophenschutz, Rettungsdienst, Eventmedizin, Übungsszenarien

---

## 🛠 Features

### ✅ Patientenverwaltung
- Erstellen neuer Patienten inkl. automatischer Nummerierung
- Erfassung von:
  - Alter, Geschlecht, Verdachtsdiagnose, Standort
  - Trupps (mehrere möglich)
  - RTM (mehrere möglich)
- Nachforderung von Ressourcen (Tragetrupp, Polizei, RTW, NEF)

### 📊 Statusverwaltung
- Statusänderung über farbcodierte Buttons:
  - `gemeldet` (rot)
  - `disponiert` (gelb)
  - `in Behandlung` (grün)
  - `verlegt in UHS` (hellblau)
  - `Behandlung in UHS` (blau)
  - `Transport in KH` (grau)
  - `Entlassen` (grau)
- Automatische Einordnung in Sektionen (Aktiv, In UHS, Entlassen)

### 🕒 Verlauf & Historie
- Automatische Historieneinträge bei Statuswechsel, Nachforderungen etc.
- Eigene Einträge über Freitextfeld mit Enter
- Klar strukturierte Darstellung je Patient
- Vermerk bei Nachforderung & Verfügbarkeit („disponiert“)

---

## 🧠 Lokale Speicherung
- Alle Daten werden automatisch im Browser gespeichert (`LocalStorage`)
- Kein Server notwendig
- Button zum Zurücksetzen aller Daten

---

## 🌐 Bedienkomfort
- Moderne, responsive Benutzeroberfläche
- Übersichtliche Kartenansicht für Patienten
- Optische Trennung der Patientenstatus
- Intuitive Eingabe über Buttons, Dropdowns und Freitextfelder
- Kompakte Darstellung, ideal für Tablets und Laptops im Einsatz

---

## 📦 Verwendete Technologien
- HTML5  
- CSS3  
- Vanilla JavaScript  
- LocalStorage (zur lokalen Datenspeicherung im Browser)

---

## 💾 Projektstruktur

```bash
/
├── index.html           # Hauptprojektdatei mit gesamter Logik
├── README.md            # Projektdokumentation
```

---

## 🚀 Nutzung / Installation

1. `index.html` im Browser öffnen (lokal oder auf einem Webserver)
2. Patienten erfassen und verwalten
3. Daten bleiben automatisch erhalten (solange LocalStorage nicht geleert wird)

> Keine Installation oder Internetverbindung notwendig!

---

## 🔮 Geplante Erweiterungen

- Exportfunktion (PDF / CSV)
- Filter- und Suchfunktion nach Status oder Trupp
- Touch-optimierte Oberfläche
- Mehrsprachigkeit (z. B. DE / EN)
- Benutzerverwaltung (optional)

---

## 👨‍💻 Entwickler

Projektleitung & Umsetzung:  
**Chris Rossol**

---

📣 Für Feedback, Vorschläge oder Weiterentwicklung:  
Gerne ein Issue eröffnen oder forken!
