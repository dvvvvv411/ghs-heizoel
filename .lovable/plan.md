

# Branding-Update: Valentin GmbH -> GHS Heizoel

## Uebersicht
Alle Branding-Informationen werden von "Valentin GmbH" auf "GHS Beteiligungs GmbH" / "GHS Heizoel" umgestellt. Betroffen sind 15 Dateien.

## Ersetzungs-Mapping

| Alt | Neu |
|-----|-----|
| Valentin GmbH | GHS Beteiligungs GmbH |
| Valentin Heizoel (Shopname) | GHS Heizoel |
| Rheinallee 187 | Johannes-Kepler-Str. 14 |
| 55120 Mainz | 55129 Mainz |
| HRB 4 | HRB 3983 |
| Julia Muendler | Florian Schmitt |
| DE280303368 | DE243309984 |
| info@valentin-heizoel.de | info@ghs-heizoel.de |
| 06131-6365855 | 06131-6365853 |
| valentin-heizoel.de | ghs-heizoel.de |
| checkout.valentin-heizoel.de | checkout.ghs-heizoel.de |

## Betroffene Dateien

### 1. `index.html`
- Title, meta description, keywords, author

### 2. `src/pages/Index.tsx`
- Helmet title und meta description

### 3. `src/pages/Impressum.tsx`
- Alle Firmendaten, Adresse, Telefon, E-Mail, HRB, USt-IdNr, Geschaeftsfuehrung

### 4. `src/pages/AGB.tsx`
- Helmet, Firmenname und Adresse im Fliesstext

### 5. `src/pages/Datenschutz.tsx`
- Helmet, Firmenname, Adresse, E-Mail

### 6. `src/pages/Widerrufsrecht.tsx`
- Helmet, Firmenname, Adresse, E-Mail (3x im Text)

### 7. `src/pages/AboutUs.tsx`
- Helmet, Firmenname, Adresse, E-Mail, HRB, USt-IdNr

### 8. `src/pages/Products.tsx`
- Helmet title

### 9. `src/pages/Services.tsx`
- Helmet title

### 10. `src/components/Header.tsx`
- E-Mail, Telefon, alt-Texte fuer Logo

### 11. `src/components/Footer.tsx`
- Firmenname, E-Mail, Telefon, Adresse

### 12. `src/components/CompanySection.tsx`
- Firmenname im Text und alt-Text

### 13. `src/components/ServiceContact.tsx`
- E-Mail

### 14. `src/components/DeliverySection.tsx`
- E-Mail

### 15. `src/components/PriceCalculator.tsx`, `HorizontalPriceCalculator.tsx`, `MobilePriceCalculator.tsx`
- Checkout-URL Domain und Fehler-E-Mail

## Technische Details
- Einfache Suchen-und-Ersetzen-Aenderungen in allen Dateien
- Keine strukturellen Aenderungen noetig
- Checkout-URL Domain wird von `checkout.valentin-heizoel.de` auf `checkout.ghs-heizoel.de` geaendert
- Tel-Links: `+4961316365855` wird zu `+4961316365853`
