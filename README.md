# Stahlbalken mit Stegöffnung

Web-Version des Excel-Eingabetools „Stahlbalken_mit_Stegöffnung.xlsx“.
Läuft komplett im Browser (keine Server-Berechnung), funktioniert offline und lässt sich als Desktop-App installieren.

## Veröffentlichen über GitHub Pages

1. Neues Repository anlegen (z. B. `stegoeffnung`), Sichtbarkeit nach Wunsch.
2. Alle Dateien dieses Ordners hochladen (`index.html`, `manifest.json`, `sw.js`, Ordner `icons/`).
3. Repository → **Settings → Pages** → Source: „Deploy from a branch“, Branch `main`, Ordner `/ (root)` → Save.
4. Nach ca. 1 Minute ist das Tool erreichbar unter `https://<benutzername>.github.io/stegoeffnung/`.

## Als Desktop-App installieren

Seite in **Chrome oder Edge** öffnen → in der Adressleiste auf das Symbol „App installieren“ klicken
(Edge: Menü → Apps → „Diese Website als App installieren“).
Danach startet das Tool in einem eigenen Fenster mit Startmenü-/Desktop-Verknüpfung und funktioniert auch ohne Internet.

## Bedienung

- Links Eingaben, rechts Ergebnis, Skizze mit Ausnutzung an den vier Nachweisstellen und Nachweistabelle – alles live.
- Oben **Eingabe / Protokoll** umschalten: Das Protokoll zeigt den Ausdruck in Excel-Optik.
- **Protokoll drucken**: zweiseitiger A4-Ausdruck mit Briefkopf. Im Druckdialog „Hintergrundgrafiken“ aktiviert lassen, Ränder „Keine“ bzw. „Standard“.
- **Speichern / Öffnen**: Eingaben als `.json`-Datei ablegen (z. B. im Projektordner) und später wieder laden.
- Die letzten Eingaben bleiben im Browser gespeichert.

## Updates

`index.html` ändern, hochladen und in `sw.js` die Versionsnummer (`stegoeffnung-v2` → `v3`) erhöhen.
