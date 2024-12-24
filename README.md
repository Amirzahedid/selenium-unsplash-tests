# Selenium-Tests für Unsplash

Dieses Projekt enthält Selenium WebDriver-Tests, um die Funktionalitäten der Website [Unsplash](https://unsplash.com/de) zu überprüfen. Es wurde als Teil der akademischen Übung **"Prüfungsleistung 3.2"** erstellt.

## Funktionen

Das Projekt umfasst folgende Testfälle:

### Testfall 1: Bildersuche
- Suche nach dem Schlüsselwort **"Hochschule"**.
- Überprüfen, ob mehr als 10 Bilder angezeigt werden.
- Ergebnisse nach **"Neueste"** filtern.
- Das erste Bild aus den Ergebnissen auswählen.
- Das Veröffentlichungsdatum des ausgewählten Bildes ausgeben.

### Testfall 2: Entdecken und Herunterladen
- Den Bereich "Fotos entdecken" öffnen.
- Das erste Bild auswählen.
- Das ausgewählte Bild herunterladen.
- Überprüfen, ob der Download erfolgreich war.

## Voraussetzungen

- Installiertes Python 3.x
- Installierte Selenium WebDriver-Bibliothek
- Installierter Google Chrome-Browser
- ChromeDriver in einer Version, die mit Ihrem Chrome-Browser kompatibel ist

## Installation

1. Repository klonen:
   ```bash
   git clone https://github.com/Amirzahedid/selenium-unsplash-tests.git
   ```
2. Benötigte Abhängigkeiten installieren:
   ```bash
   pip install selenium
   ```

## Verwendung

1. Öffnen Sie das Jupyter Notebook `PL32_Selenium_A.ipynb`.
2. Führen Sie die Zellen Schritt für Schritt aus, um die Tests durchzuführen.
3. Stellen Sie sicher, dass der ChromeDriver korrekt eingerichtet und im Systempfad verfügbar ist.

## Hinweise

- Im Projekt werden `time.sleep()`-Aufrufe verwendet, um sicherzustellen, dass die Website vollständig geladen ist. Passen Sie diese Werte je nach Ihrer Internetgeschwindigkeit an.
- Die Download-Funktionalität erfordert entsprechende Berechtigungen und Konfigurationen, um manuelle Eingabeaufforderungen zu vermeiden.

## Danksagungen

- **Entwickler**: Amir Zahedidarehshoori, Seyedehhadiseh Abbaspoor
- **Zweck**: Akademische Übung zum Erlernen des Umgangs mit Selenium WebDriver.

## Lizenz

Dieses Projekt ist nur für Bildungszwecke vorgesehen und nicht für die kommerzielle Nutzung lizenziert.

