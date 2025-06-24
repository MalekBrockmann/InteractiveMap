# InteractiveMap - Global Event Tracker

Eine interaktive Europa-Karte mit aktuellen Nachrichten aus europäischen Ländern.

## Features

- **Vollbild-Karte**: Die Karte nimmt den gesamten Bildschirm ein
- **Interaktive Länder**: Klicken Sie auf ein Land, um aktuelle Nachrichten zu sehen
- **Farbkodierung**: Länder werden basierend auf den Nachrichten-Kategorien eingefärbt:
  - 🔴 Rot: Politische Nachrichten
  - 🔵 Blau: Kulturelle Nachrichten
  - 🟢 Grün: Gesellschaftliche Nachrichten
  - ⚪ Grau: Gemischte Kategorien
- **Nachrichten-Popups**: Nachrichten werden direkt auf der Karte in Popup-Fenstern angezeigt
- **Dropdown-Menü**: Länderauswahl im oberen linken Bereich der Karte
- **Automatische Übersetzung**: Nicht-deutsche Nachrichten werden automatisch ins Deutsche übersetzt

## Technologien

- **HTML5**: Struktur der Webseite
- **CSS3**: Styling und Layout
- **JavaScript**: Interaktivität und API-Integration
- **Leaflet.js**: Interaktive Karten
- **GNews API**: Nachrichten-Daten
- **Google Translate API**: Übersetzungsfunktion

## Installation

1. Klonen Sie das Repository:
```bash
git clone https://github.com/MalekBrockmann/InteractiveMap.git
```

2. Öffnen Sie `index.html` in einem Webbrowser

## Konfiguration

### API-Schlüssel

Sie benötigen folgende API-Schlüssel:

1. **GNews API**: Für Nachrichten-Daten
   - Registrieren Sie sich auf [GNews](https://gnews.io/)
   - Ersetzen Sie den Token in der `fetchCountryNews` Funktion

2. **Google Translate API**: Für Übersetzungen
   - Erstellen Sie ein Google Cloud Projekt
   - Aktivieren Sie die Translate API
   - Ersetzen Sie `YOUR_GOOGLE_TRANSLATE_API_KEY` in der `translateToGerman` Funktion

## Verwendung

1. Öffnen Sie die Webseite in einem Browser
2. Klicken Sie auf ein Land in der Karte oder wählen Sie es aus dem Dropdown-Menü
3. Ein Popup mit aktuellen Nachrichten aus dem Land wird angezeigt
4. Das Land wird entsprechend der Nachrichten-Kategorien eingefärbt

## Projektstruktur

```
InteractiveMap/
├── index.html          # Haupt-HTML-Datei
├── styles.css          # CSS-Styles
├── README.md           # Projekt-Dokumentation
└── Bilder/             # Bild-Assets
```

## Nachrichten-Kategorien

Die Nachrichten werden automatisch in folgende Kategorien eingeteilt:

- **Politik**: Regierung, Wahlen, Parlament, Minister, Parteien
- **Kultur**: Kunst, Museen, Theater, Ausstellungen, Festivals, Musik
- **Gesellschaft**: Bildung, Gesundheit, Umwelt, Arbeit, soziale Themen

## Browser-Kompatibilität

- Chrome (empfohlen)
- Firefox
- Safari
- Edge

## Lizenz

Dieses Projekt steht unter der MIT-Lizenz.

## Kontakt

Für Fragen oder Anregungen erstellen Sie bitte ein Issue auf GitHub. 