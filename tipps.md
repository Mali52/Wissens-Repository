# 🛠️ Git Tipps & Tricks

> Autor: Mehmet Ali Karayusuf  
> Datei: `tipps.md`  
> Ziel: Praktische Git-Befehle

---

## 🔹 1. Repository starten & verbinden

```bash
git init                       # Neues Git-Repository lokal erstellen
git clone <url>               # Bestehendes Projekt klonen
git remote add origin <url>   # Lokales Projekt mit GitHub verbinden
git remote -v                 # Verbundene Remotes anzeigen
```

---

## 🔹 2. Änderungen vorbereiten & festhalten

```bash
git status                    # Aktuelle Änderungen anzeigen
git add .                     # Alle Dateien zum Commit vormerken
git commit -m "Beschreibung"  # Änderungen committen mit Nachricht
git log --oneline             # Commit-History kompakt
```

💡 **Tipp:** Schreibe klare Commit-Nachrichten wie `Fix: Rechtschreibung README.md`

---

## 🔹 3. Push, Pull & Remote-Arbeit

```bash
git push origin main                        # Änderungen zu GitHub senden
git pull origin main                        # Änderungen von GitHub holen
git push --set-upstream origin branch-name  # Upstream-Verknüpfung erstellen
```

💬 `origin` ist der Spitzname für dein GitHub-Repo.

---

## 🔹 4. Datei-Wiederherstellung & Zwischenablage

```bash
git restore datei.txt       # Datei auf letzte Version zurücksetzen
git stash                   # Änderungen kurzzeitig speichern
git stash pop               # Gespeicherte Änderungen wiederherstellen
```

---

## 🔹 5. Aufräumen & Übersicht behalten

```bash
git diff                    # Zeigt Unterschiede vor dem Commit
git add -p                  # Änderungen interaktiv auswählen
git clean -f                # Nicht getrackte Dateien löschen (Achtung!)
```