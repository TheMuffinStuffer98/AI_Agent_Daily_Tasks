# Assistent-App auf GitHub Pages einrichten

Dauer: etwa 10 Minuten. Es wird nichts programmiert, nur hochgeladen.

## 1. GitHub-Konto und Projekt anlegen
1. Auf https://github.com ein kostenloses Konto anlegen (falls noch keins vorhanden).
2. Oben rechts auf **+** → **New repository**.
3. Repository name: `assistent` · Public · Haken bei **Add a README file** · **Create repository**.

## 2. Dateien hochladen
1. Im neuen Repository auf **Add file** → **Upload files**.
2. Diese Dateien hineinziehen (alle aus diesem Ordner):
   `index.html`, `sw.js`, `manifest.webmanifest`, `icon-180.png`, `icon-192.png`, `icon-512.png`
3. Unten auf **Commit changes**.

## 3. Veröffentlichen
1. Im Repository auf **Settings** → links **Pages**.
2. Unter *Build and deployment* → Source: **Deploy from a branch** → Branch: **main**, Ordner **/ (root)** → **Save**.
3. Nach 1–2 Minuten steht oben die Adresse, z. B. `https://DEINNAME.github.io/assistent/`.

## 4. Auf dem iPhone einrichten
1. Die Adresse in **Safari** öffnen (nicht in Chrome, sonst fehlt "Zum Home-Bildschirm").
2. Teilen-Symbol → **Zum Home-Bildschirm** → **Hinzufügen**.
3. Die App vom Home-Bildschirm starten. Dann unter **Mehr**:
   - **Benachrichtigungen erlauben** antippen und bestätigen.
   - **Bonerkennung für offline vorbereiten** antippen (lädt einmalig ca. 15 MB, danach offline).
4. Beim ersten Tippen auf das Mikrofon den Zugriff erlauben.

## Was offline geht – und was nicht
- Offline: App-Start, Haushaltsbuch, Budgets, Notizen, Erinnerungen, Termine, Kassenbon-Erkennung, Texteingabe von Befehlen.
- Nur mit Internet: die **Spracherkennung** (Safari schickt das Audio an Apple). Ohne Netz einfach tippen.

## Updates einspielen
Neue `index.html` (oder andere Dateien) im Repository über **Add file → Upload files** hochladen und die alten dabei ersetzen. Die App holt die neue Version beim nächsten Start mit Internet.

## Backup
Alle Daten liegen nur im Safari-Speicher des iPhones. Unter **Mehr → Backup kopieren** regelmäßig sichern (z. B. in eine Notiz einfügen). Wenn Safari-Daten gelöscht werden, sind auch die Einträge weg.
