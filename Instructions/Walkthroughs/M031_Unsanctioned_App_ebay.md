---
wts:
    title: '12 - Defender Cloud Apps'   
    module: '02 - Erkunden'
---


# Schritt-für-Schritt-Anleitung: eBay als unsanctioned im App-Katalog markieren

## 1. Voraussetzungen
- Rolle: **Sicherheitsadministrator** oder **Globaler Administrator** erforderlich
- Zugriff auf das [Microsoft Defender for Cloud Apps Portal](https://portal.cloudappsecurity.com)

## 2. Anmeldung
- Melde dich im Microsoft Defender for Cloud Apps Portal an.

## 3. App-Katalog öffnen
- Gehe zu **Untersuchen → App-Katalog**.
- Suche nach der App **eBay**.

## 4. App auswählen
- Klicke auf den Namen der App (eBay), um die Detailseite zu öffnen.

## 5. Status ändern
- Oben rechts die Option **Markieren als unsanctioned** auswählen.
- Klicke darauf, um die App als „nicht genehmigt“ zu kennzeichnen.

## 6. Auswirkungen
- Die App wird nun als **unsanctioned** markiert.
- Wenn die Integration mit **Microsoft Defender for Endpoint** aktiv ist, wird der Zugriff auf diese App auf verwalteten Geräten blockiert.

## 7. Überwachung
- Überprüfe im **App-Katalog**, ob die App den Status „unsanctioned“ hat.
- Optional: Erstelle eine **App-Steuerungsrichtlinie**, um die Blockierung zusätzlich durchzusetzen.
