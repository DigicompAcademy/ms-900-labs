---
wts:
    title: '05 - Entra M365 Gruppe'   
    module: '01 - Grundlagen'
---


## Anleitung: Erstellen einer Microsoft 365 Gruppe in Microsoft Entra

### ✅ Schritt 1: Anmelden
1. Gehe zu https://entra.microsoft.com.
2. Melde dich mit einem Konto an, das über **Administratorrechte** verfügt (z. B. Globaler Administrator oder Benutzeradministrator).

---

### ✅ Schritt 2: Navigiere zu Gruppen
1. Im linken Menü wähle **Identität** → **Gruppen**.
2. Klicke auf **Alle Gruppen**.

---

### ✅ Schritt 3: Neue Gruppe erstellen
1. Klicke oben auf **Neue Gruppe**.
2. Wähle den **Gruppentyp**:
   - **Microsoft 365** (für Teams, Planner, SharePoint, Outlook-Gruppen).
3. Gib die erforderlichen Informationen ein:
   - **Name der Gruppe** (z. B. „Marketing-Team“).
   - **Gruppenbeschreibung** (optional, aber empfohlen).
   - **E-Mail-Adresse** für die Gruppe (wird automatisch generiert, kann angepasst werden).

---

### ✅ Schritt 4: Einstellungen festlegen
- **Mitgliedschaftstyp**:
  - **Zugewiesen** (du fügst Mitglieder manuell hinzu).
  - **Dynamisch** (Mitglieder basierend auf Regeln, z. B. Abteilung = „Marketing“).
- **Eigentümer hinzufügen** (mindestens einen).
- **Mitglieder hinzufügen** (optional, kann später erfolgen).

---

### ✅ Schritt 5: Erstellen
- Überprüfe die Angaben und klicke auf **Erstellen**.
- Die Gruppe wird erstellt und ist sofort in Microsoft 365 verfügbar (Teams, Outlook, SharePoint).

---

### 🔍 Zusätzliche Tipps
- **Namenskonventionen** beachten (z. B. „DE-Marketing-M365“).
- Prüfe die **Richtlinien für Gruppen** in Entra (z. B. Ablaufdatum, Namensrichtlinien).
- Für **dynamische Gruppen** musst du eine Regel definieren (z. B. `user.department -eq "Marketing"`).
