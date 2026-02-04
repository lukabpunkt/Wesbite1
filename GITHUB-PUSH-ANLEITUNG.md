# Code zu GitHub pushen

Repository: **https://github.com/lukabpunkt/Website-Meisterreinigung.git**

## 1. Git installieren (falls noch nicht geschehen)

- Download: https://git-scm.com/download/win  
- Installation durchführen (Standard-Optionen reichen).  
- **Terminal/CMD neu öffnen** danach.

## 2. In den Projektordner wechseln

```bash
cd "C:\Users\lukab\OneDrive\Desktop\Meisterreinigung"
```

## 3. Git-Repository einrichten und pushen

```bash
git init
git remote add origin https://github.com/lukabpunkt/Website-Meisterreinigung.git
git add .
git commit -m "Landingpage Meisterreinigung Wietmarschen"
git branch -M main
git push -u origin main
```

## 4. Bei Login-Abfrage

- **Username:** Ihre GitHub-Benutzername (z. B. `lukabpunkt`)
- **Passwort:** Ein **Personal Access Token** (kein normales Passwort)
  - GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic)
  - "Generate new token" → z. B. "repo" anhaken → Token kopieren und beim `git push` als Passwort eingeben

---

**Hinweis:** Das Logo verwendet lokal den Pfad `../../Bilder/Waschmaschinenlogo.png`. Für die Live-Website das Bild in den Projektordner legen und in der HTML-Datei den Pfad z. B. auf `Waschmaschinenlogo.png` oder `bilder/Waschmaschinenlogo.png` ändern.
