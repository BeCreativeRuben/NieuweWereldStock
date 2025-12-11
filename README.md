# Nieuwe Wereld Stock Inventaris

Een eenvoudig, offline-first web-gebaseerd voorraadbeheersysteem voor café Nieuwe Wereld.

## Features

- 📊 **Voorraadbeheer**: Track 25 producten met Zuipbakken (volle bakken) en Zuip (losse eenheden)
- 📅 **Weekelijkse logging**: Sla wekelijkse voorraad snapshots op met timestamps
- 📚 **Geschiedenis**: Bekijk tot 52 weken aan geschiedenis
- 📥 **CSV Export**: Exporteer alle data naar CSV voor verdere analyse
- 🎨 **Café thema**: Warme bruine kleuren passend bij een café sfeer
- 📱 **Mobiel vriendelijk**: Responsive design voor gebruik op tablets en smartphones
- 💾 **Offline-first**: Werkt volledig offline met localStorage

## Gebruik

1. Open `index.html` in je webbrowser
2. Vul de voorraad in voor elke product
3. Klik op "Opslaan" om de huidige week op te slaan (velden worden automatisch gereset naar 0)
4. Klik op "Nieuwe Week" om een nieuwe week te starten
5. Bekijk geschiedenis door op de geschiedenis sectie te klikken
6. Exporteer naar CSV met de "Exporteer CSV" knop

## Berekening

- **Totaal Eenheden** = (Zuipbakken × 24) + Zuip
- 1 Zuipbak = 24 eenheden

## Technologie

- Pure HTML, CSS en JavaScript (geen frameworks)
- localStorage voor data opslag
- Offline-first architectuur

## Browser Ondersteuning

Werkt in alle moderne browsers die localStorage ondersteunen.

