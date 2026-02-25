

# Branding-Farbwechsel: Rot (#e03c20) zu Gruen (#19d00b)

## Zusammenfassung
Alle roten Branding-Farben im gesamten Projekt werden durch das neue Gruen **#19d00b** (und passende dunklere/hellere Varianten) ersetzt.

Neue Farbpalette:
- **Hauptfarbe**: #19d00b (statt #e03c20)
- **Dunkel**: #14a809 (statt #c73418)
- **Hell**: #2eef1a (statt #f25538)

## Betroffene Dateien

### 1. `tailwind.config.ts`
- `hill.green` Palette: #e03c20 -> #19d00b, #c73418 -> #14a809, #f25538 -> #2eef1a
- `accent-orange` Palette: Komplett auf Gruen-Toene umstellen (50-900 Skala mit gruenen Werten)
- `primary` Palette: DEFAULT und 500 -> #19d00b, 600 -> #14a809, plus passende helle Toene (50-400)
- `boxShadow`: Alle rgba(224, 60, 32, ...) -> rgba(25, 208, 11, ...)

### 2. `src/index.css`
- CSS Custom Properties: --hill-green, --hill-green-dark, --hill-green-light
- --gradient-mesh-1/2/3 Werte
- Focus ring Farbe: ring-[#e03c20] -> ring-[#19d00b]
- .gradient-text-premium: Farbwerte ersetzen
- .gradient-border: Farbwerte ersetzen
- .mesh-gradient: rgba-Werte anpassen
- .glow-pulse Keyframe: rgba-Werte anpassen

### 3. `src/components/HeroSection.tsx`
- Inline-Style mit #e03c20 im Grid-Pattern -> #19d00b

### Technische Details
- Alle Vorkommen von `#e03c20` -> `#19d00b`
- Alle Vorkommen von `#c73418` -> `#14a809`
- Alle Vorkommen von `#f25538` -> `#2eef1a`
- Alle `rgba(224, 60, 32, ...)` -> `rgba(25, 208, 11, ...)`
- Alle `rgba(242, 85, 56, ...)` -> `rgba(46, 239, 26, ...)`
- Alle `rgba(199, 52, 24, ...)` -> `rgba(20, 168, 9, ...)`
- Die Rot-basierte 50-900 Skala wird durch eine gruene Skala ersetzt (z.B. 50: #f0fdf0, 100: #dcfce7, 200: #bbf7d0, etc.)

