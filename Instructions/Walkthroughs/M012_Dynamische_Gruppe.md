---
wts:
    title: '05 - Entra M365 Dynamische Gruppe'   
    module: '01 - Grundlagen'
---


# Schritt-für-Schritt-Anleitung: Dynamische Microsoft 365 Gruppe in Entra erstellen (basierend auf Abteilungsattribut)

## Voraussetzungen
- Entra ID P1 oder P2 Lizenz
- Rolle: Global-Admin, Gruppen-Admin oder Benutzer-Admin

---

## Schritt 1: Anmeldung im Entra Admin Center
1. Öffne [https://entra.microsoft.com](https://entra.microsoft.com).
2. Melde dich mit deinem Administrator-Konto an.



---

## Schritt 2: Neue Gruppe erstellen
1. Navigiere im linken Menü zu **Gruppen → Alle Gruppen**.
2. Klicke oben auf **+ Neue Gruppe**.



---

## Schritt 3: Gruppentyp und Mitgliedschaft festlegen
1. Wähle **Microsoft 365** als Gruppentyp.
2. Setze **Mitgliedschaftstyp** auf *Dynamische Benutzer*.
3. Gib einen **Gruppennamen** und eine **Beschreibung** ein.



---

## Schritt 4: Dynamische Abfrage hinzufügen
1. Klicke auf **Dynamic user members → Regel hinzufügen**.
2. Im Rule Builder:
   - Eigenschaft: `department`
   - Operator: `equals`
   - Wert: z. B. `Sales`
3. Vorschau anzeigen und auf **Speichern** klicken.



---

## Schritt 5: Regel prüfen und Gruppe erstellen
1. Überprüfe die generierte Regel-Syntax:
   ```
   (user.department -eq "Sales")
   ```
2. Für mehrere Abteilungen:
   ```
   (user.department -eq "Sales") or (user.department -eq "Marketing")
   ```
3. Klicke auf **Erstellen**.



---

## Schritt 6: Mitgliedschaft prüfen
1. Nach einigen Minuten wird die Gruppe erstellt.
2. Öffne die Gruppe und prüfe unter **Mitglieder**, ob die Benutzer korrekt hinzugefügt wurden.


---

### Tipps
- Stelle sicher, dass das Attribut „Abteilung“ bei den Benutzern gepflegt ist.
- Für komplexe Regeln nutze den Syntax-Editor.
- Administratoren können die Verarbeitung unter **MembershipRuleProcessingState** aktivieren.
