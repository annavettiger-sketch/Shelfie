# Shelfie ISBN Scanner

Eine einfache Handy-Web-App: ISBN/Barcode scannen -> Google Books suchen -> Bewertung anzeigen.

## Lokal starten

```bash
npm install
npm run dev
```

Dann im Browser öffnen:

```text
http://localhost:3000
```

## Auf Vercel veröffentlichen

1. Projekt auf GitHub hochladen.
2. Auf vercel.com mit GitHub einloggen.
3. "Add New Project" wählen.
4. Dieses Repository importieren.
5. Framework sollte automatisch "Next.js" sein.
6. Deploy klicken.

## Nutzung auf iPhone/iPad

Nach dem Deploy die Vercel-Adresse in Safari öffnen:

Teilen -> Zum Home-Bildschirm

Dann wirkt es wie eine normale App.

## Hinweis

Google Books zeigt nicht bei jedem Buch eine Bewertung an. Falls keine Bewertung vorhanden ist, zeigt die App "Keine Bewertung".
