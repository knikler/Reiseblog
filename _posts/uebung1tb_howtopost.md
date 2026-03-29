---
layout: default
title: "Uebung Timon erstellt ein cheat-sheet"
date: 2026-03-29
---

# Git & Terminal Cheat-Sheet

### Projekt auf den neuesten Stand bringen
`git pull`
Aktuellen Stand vom Server herunterladen.

### Branch-Management
`git switch timon`
In meinen eigenen Branch wechseln.

`git checkout <name>` oder `git switch <name>`
Zwischen existierenden Branches wechseln.

### Änderungen speichern (Lokal)
`git add <datei>`
Ein spezifisches File für den Commit vormerken.

`git add .`
Alle geänderten Files im aktuellen Ordner vormerken.

`git commit -m "deine nachricht"`
Die Änderungen mit einer Beschreibung festschreiben.

### Hochladen
`git push`
Deine Commits auf GitHub hochladen.

### Dateien verwalten
`mv datei_alt datei_neu`
Datei umbenennen.

`mv datei ordner/`
Datei in einen Ordner verschieben.

---

### Vim Editor (Direkt im Terminal)
`vim dateiname.md` - Datei öffnen

| Aktion | Taste | Was passiert? |
| :--- | :--- | :--- |
| **Schreiben** | `i` | Aktiviert den `-- INSERT --` Modus. |
| **Stoppen** | `Esc` | Zurück in den Befehlsmodus. |
| **Speichern** | `:wq` | Speichern und Beenden (nach Esc). |
| **Abbrechen** | `:q!` | Schließen ohne Speichern (nach Esc). |

---

### GitHub Verbindung (Einmalig)
1. `brew install gh` (GitHub CLI installieren)
2. `gh auth login` (Login-Prozess starten)
3. Folge den Schritten: `GitHub.com` -> `HTTPS` -> `Yes` -> `Login with a web browser`.
