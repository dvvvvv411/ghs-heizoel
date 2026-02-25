

# Farbupdate: Emerald Green (#10b981)

## Zusammenfassung
Das aktuelle Neon-Gruen (#19d00b) wird durch ein modernes **Emerald Green #10b981** ersetzt -- ein elegantes, professionelles Gruen das bei vielen modernen Tech-Marken beliebt ist.

**Neue Farbpalette:**
- Hauptfarbe: **#10b981** (Emerald)
- Dunkel: **#059669** (Emerald Dark)
- Hell: **#34d399** (Emerald Light)

## Betroffene Dateien

### 1. `tailwind.config.ts`
- `hill` Palette: #19d00b -> #10b981, #14a809 -> #059669, #2eef1a -> #34d399
- `accent-orange` und `primary` Paletten: Komplette 50-900 Skala auf Emerald-Toene (Tailwind Emerald Scale)
- `boxShadow`: Alle rgba(25, 208, 11, ...) -> rgba(16, 185, 129, ...)
- `glow-pulse` Keyframe: rgba-Werte anpassen

### 2. `src/index.css`
- CSS Custom Properties: --hill-green -> #10b981, --hill-green-dark -> #059669, --hill-green-light -> #34d399
- --gradient-mesh Werte anpassen
- Focus ring: ring-[#19d00b] -> ring-[#10b981]
- Gradient- und Glow-Utilities: Alle Farbwerte aktualisieren

### 3. `src/components/HeroSection.tsx`
- Inline-Style Grid-Pattern: #19d00b -> #10b981

### Farbmapping
| Alt | Neu | Verwendung |
|-----|-----|-----------|
| #19d00b | #10b981 | Hauptfarbe |
| #14a809 | #059669 | Dunkel/Hover |
| #2eef1a | #34d399 | Hell/Akzent |

### Emerald 50-900 Skala
- 50: #ecfdf5
- 100: #d1fae5
- 200: #a7f3d0
- 300: #6ee7b7
- 400: #34d399
- 500: #10b981
- 600: #059669
- 700: #047857
- 800: #065f46
- 900: #064e3b

