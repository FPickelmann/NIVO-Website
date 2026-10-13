# NIVO Bottle Systems – Schulmodellunternehmen

Statische, responsive Website für GitHub Pages. Alle Personen, Firmenangaben, Produkte und dargestellten Geschäftsvorgänge sind fiktiv. Die Produktbilder sind Designstudien aus dem bereitgestellten NIVO-Konzept-PDF.

## Veröffentlichung auf GitHub Pages
1. Auf github.com ein neues öffentliches Repository anlegen, z. B. `nivo-website`.
2. Alle Dateien und den Ordner `assets` aus diesem Projekt ins Stammverzeichnis des Repositorys hochladen.
3. Unter **Settings → Pages → Build and deployment** die Option **Deploy from a branch** auswählen, Branch `main`, Ordner `/(root)`, dann speichern.
4. Die Seite ist nach der Veröffentlichung üblicherweise unter `https://BENUTZERNAME.github.io/nivo-website/` erreichbar.

## Lernwelt: Apps hinzufügen
In `script.js` im Array `sampleApps` neue Einträge anlegen:

```js
{title:'Neues Lernspiel', desc:'Beschreibung', icon:'★', date:'2026-10-14', url:'https://example.org/spiel'}
```

Neueste Einträge werden nach `date` absteigend angezeigt. Die Suche filtert Titel und Beschreibung. Links funktionieren auch zu extern gehosteten Anwendungen. Die Beispiel-Apps enthalten bewusst keine funktionsfähigen Links.

## Hinweis zur Anmeldung
Die Eingabe eines beliebigen Namens und einer beliebigen Zahlenfolge ist nur eine Einstiegshürde, **keine Authentifizierung**. Es dürfen ausschließlich öffentliche/fiktive Unterrichtsinhalte eingebunden werden. Keine echten Zugangsdaten eingeben.

## Weiterentwicklung
Das GitHub-Pages-Projekt benötigt keinen Server. Für echte gemeinsame Bearbeitung mit dauerhaft synchronisiertem Datenstand ist ein externer Datendienst erforderlich. Bilder sind als Designstudien gekennzeichnet; reale Produktleistungsnachweise liegen nicht vor.
