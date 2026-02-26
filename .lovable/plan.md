

# Favicon austauschen und alte Dateien entfernen

## Aenderungen

### 1. Neues Favicon kopieren
- `user-uploads://ghsfavicon.png` wird nach `public/favicon.png` kopiert (ueberschreibt die alte Datei)

### 2. Altes `favicon.ico` loeschen
- `public/favicon.ico` wird entfernt, da nur noch das neue PNG-Favicon verwendet wird

### 3. `index.html` bleibt unveraendert
- Der bestehende Verweis `<link rel="icon" href="/favicon.png" type="image/png" />` passt bereits, da das neue Favicon unter demselben Dateinamen abgelegt wird

## Hinweis
Die Seitentitel und -beschreibungen in `index.html` und allen Seiten-Komponenten (Helmet) sind bereits auf das GHS-Branding umgestellt. Es sind keine weiteren Text-Aenderungen noetig.

