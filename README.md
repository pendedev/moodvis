# Moodvis Beta

**Willkommen zur Moodvis Beta**

Die Betaphase dient dazu Feedback zu sammeln und zur allgemeinen Fehlerbehebung bei verschiedenen Settings. 

---

### 🧪 Feedback & Support
Falls du einen Fehler entdeckst oder eine Idee hast:
* Erstelle ein **Issue** für Fehlermeldungen.
* Starte eine **Discussion** für Designvorschläge und allgemeinen Austausch.
* Zeig dein Dashboard in den Discussions unter der Kategorie **Show and Tell**

---

### 📜 Changelog

#### [v0.6.0]
* Objektbrowser zeigt bei Ordnern jetzt den Namen und ID an
* Bei Chartobjekt ist Diagramm 1 optional jetzt auch als Liniendiagramm einstellbar
* Für Diagramm 1 bis 3 vom Chartobjekt kann jetzt jeweils eine eigene Farbe ausgewählt werden
* Größeneinstellung für Kacheln und Widgets in den Optionen geändert und in Kategorie Format umbenannt
* Widget Schalter zum Test jetzt auch auf dem Dashboard wählbar (Weitere Widgets folgen)

#### [v0.5.6]
* Objektbrowser springt direkt zum ausgewählten Datenpunkt falls schon einer
vorhanden war.
* Im Objekt Chart und das Widget Säule können beliebige Verlaufsinstanzen
angegeben werden.
* Objekt Füllstand hat jetzt einen State Datenpunkt, um ein und auszuschalten
und einen Level Datenpunkt zur Füllstandsanzeige. Min/Max und Einheit sind
jetzt auch frei wählbar. Bei Level Änderungen wird die Tendenz mit Pfeil
hoch/runter in der Kachel angezeigt.
* Einstellung „Schalten deaktivieren“ ist jetzt besser sichtbar direkt im
Bearbeiten Fenster des Objekts/Widgets platziert.
* Objekt Chart kann die Skalierung für Min/Max jetzt pro Diagramm festgelegt
werden. Bleibt das Feld leer wird weiterhin automatisch skaliert.
* Widget Text und Wert können mit der Option „Schalten aktivieren/deaktivieren
auch Werte in den Datenpunkt schreiben.
* Schaltbare Objekte und Widgets können mit der Option „Eigene Schaltwerte“
jetzt auch selbst definierte Werte für Wahr/falsch senden.
* Bei Objekten die Offline sind wird der Statuswert „Offline“ angezeigt.
* Linienbreite im Objekt Chart reduziert.
* Objekte Raum und Ebene können mit der Option „Zählen wenn aktiv“ Objekte
zählen, die gerade auf einer Unterseite des Objekts aktiv sind.
* Objekte HTML und iframe (Website) hinzugefügt.
* Aktive Hintergrundfarbe vom Objekt Chart reduziert, um Diagramm
Sichtbarkeit zu verbessern
* Allgemeine UI-Verbesserungen und Textanpassungen

#### [v0.5.0]
* Pulsiereffekt des Eingabefelds "Config Datenpunkt" entfernt sobald es nicht leer ist
* Objekte Raum und Ebene ändern jetzt ihren Status und bleiben nicht dauerhaft inaktiv/aktiv sobald ein Datenpunkt hinterlegt ist
* Infotexte bei allen Eingabefeldern der Datenpunkte hinzugefügt
* Schaltbare Datenpunkte können jetzt 1/0 oder true/false sein
* Suchfunktion in den Objektbrowser integriert
* Allgemeine Bugfixes im Objektbrowser und optische Anpassungen.
* Akkuverbrauch im Hintergrund optimiert. App trennt die Verbindung zum ioBroker sofort sobald sie im Hintergrund ist.
* Allgemeine Bugfixes und Verbesserungen

#### [v0.4.1]
* Titelleiste Bugfix bei Skalierung >100%
* Einstellungsfenster öffnet sich nicht mehr wenn man ein Widget verschiebt
* Option Bearbeitenbutton dauerhaft einblenden hinzugefügt
* Objektbrowser für breite Bildschirme optimiert (Explorerstil)
* Willkommensfenster mit Einleitung hinzugefügt
* Beim eingeben einer ioBroker URL versucht sich die App automatisch neu zu verbinden
* Neu verbinden Button neben dem ioBroker URL-Feld eingefügt
