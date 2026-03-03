

# Alle Heizölpreise seitenweit aktualisieren

## Uebersicht

Die alten Preise (0,60/0,63 bzw. 0,70/0,73) muessen ueberall auf die neuen Preise (0,90/0,93) geaendert werden. Betroffen sind 5 weitere Dateien neben den bereits aktualisierten Preisrechnern.

## Aenderungen

### 1. `src/components/HeroSection.tsx` (Zeile 102)
- "ab nur 60 Cent pro Liter" → "ab nur 90 Cent pro Liter"

### 2. `src/components/ProductSelector.tsx`
- Standard-Preis: `0.70` → `0.90` (Zeile 13)
- Premium-Preis: `0.73` → `0.93` (Zeile 25)

### 3. `src/components/ProductComparison.tsx` (Zeilen 50-51)
- Standard: `'0,70 €'` → `'0,90 €'`
- Premium: `'0,73 €'` → `'0,93 €'`

### 4. `src/components/PriceOverviewSection.tsx`
- Preiskarten-Text: `ab 0,70€` → `ab 0,90€` (Zeile 92)
- Preiskarten-Text: `ab 0,73€` → `ab 0,93€` (Zeile 119)
- Preisentwicklungs-Chart-Daten anpassen (Zeilen 17-22): alle Werte um +0.20/+0.20 erhoehen
- Mengenrabatt-Tabelle anpassen (Zeilen 37-40): Preise entsprechend erhoehen (0,90€/L, 0,88€/L, 0,87€/L, 0,86€/L)

### 5. `src/pages/DesignSystem.tsx` (Zeilen 141, 153)
- PriceCard Standard: `price={0.70}` → `price={0.90}`
- PriceCard Premium: `price={0.73}` → `price={0.93}`, `originalPrice={0.78}` → `originalPrice={0.98}`

## Nicht betroffen
- Die 3 Preisrechner-Komponenten (PriceCalculator, HorizontalPriceCalculator, MobilePriceCalculator) wurden bereits im letzten Schritt aktualisiert
- HandelsblattBanner.tsx: Die 0.70-Treffer dort sind SVG-Pfad-Koordinaten, keine Preise

