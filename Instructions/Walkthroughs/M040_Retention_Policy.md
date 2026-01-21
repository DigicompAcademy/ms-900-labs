# Schritt-für-Schritt-Anleitung: Retention Policy im Microsoft Purview Compliance Portal erstellen

## 1. Voraussetzungen
- Rolle: **Compliance-Administrator** oder **Globaler Administrator** erforderlich
- Zugriff auf das [Microsoft Purview Compliance Portal](https://compliance.microsoft.com)

## 2. Anmeldung
- Melde dich im Microsoft Purview Compliance Portal an.

## 3. Navigation zu Informationsaufbewahrung
- Gehe zu **Lösungen → Datenlebenszyklusverwaltung**.
- Wähle **Aufbewahrungsrichtlinien**.

## 4. Neue Richtlinie erstellen
- Klicke auf **+ Neue Richtlinie**.
- Wähle **Aufbewahrungsrichtlinie erstellen**.

## 5. Name und Beschreibung
- Gib einen **Namen** für die Richtlinie ein (z. B. „Retention für SharePoint & OneDrive“).
- Optional: Füge eine **Beschreibung** hinzu.

## 6. Speicherorte auswählen
- Wähle **SharePoint-Websites** und **OneDrive-Konten**.
- Für SharePoint: Gib die URL der Teamseite ein.
- Für OneDrive: Wähle die Benutzerkonten aus, für die die Richtlinie gelten soll.

## 7. Aufbewahrungseinstellungen konfigurieren
- Wähle, ob Inhalte **für einen bestimmten Zeitraum aufbewahrt** oder **gelöscht** werden sollen.
- Beispiel: „Inhalte 7 Jahre aufbewahren und dann löschen“.
- Optional: Wähle, ob die Aufbewahrung ab **Erstellungsdatum** oder **letzter Änderung** beginnt.

## 8. Überprüfen und Erstellen
- Überprüfe alle Einstellungen.
- Klicke auf **Erstellen**, um die Richtlinie zu aktivieren.

## 9. Überwachung
- Nach der Erstellung kannst du den Status unter **Aufbewahrungsrichtlinien** einsehen.
- Änderungen können bis zu 24 Stunden dauern, bis sie wirksam werden.
