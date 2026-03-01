# NutriTrack – Installationsanleitung

## 📱 Als Android App installieren

### Option 1: Direkt auf dem Gerät
1. `index.html` + `manifest.json` auf einen Webserver hochladen (z.B. GitHub Pages, Netlify, Vercel – alle kostenlos)
2. URL im Chrome-Browser auf Android öffnen
3. Chrome zeigt unten automatisch „Zum Startbildschirm hinzufügen" an
4. Tippen → Fertig! App ist installiert wie eine native App

### Option 2: Lokal testen (PC/Mac)
1. Beide Dateien in einen Ordner legen
2. Live Server starten: `npx serve .`
3. Im Browser öffnen

## ✨ Features
- 🔍 **Freitextsuche** über OpenFoodFacts (Millionen Produkte)
- 📷 **Barcode-Scanner** mit Kamera
- 📊 **Kalorien-Ring** mit Tagesübersicht
- 🥗 **Makros** Eiweiß, Kohlenhydrate, Fett, Ballaststoffe
- 🍽️ **4 Mahlzeiten** Frühstück, Mittagessen, Abendessen, Snack
- 📈 **Wochenstats** mit Balkendiagramm
- 🔥 **Streak-Tracker**
- 💾 **Offline-Fallback** mit 20 Lebensmitteln lokal
- 📤 **Datenexport** als JSON
- 🌙 **Dark Mode** (immer)
- 📴 **Komplett kostenlos** – keine Werbung, kein Abo

## 🔌 Verwendete APIs (alle kostenlos)
- **OpenFoodFacts** – Open Source Lebensmitteldatenbank
  - Freitextsuche: `https://world.openfoodfacts.org/cgi/search.pl`
  - Barcode-Lookup: `https://world.openfoodfacts.org/api/v0/product/{barcode}.json`
- **ZXing** – Open Source Barcode-Scanner Bibliothek
