# Implementierungsnotizen

## Ausgangsbasis
- Ausgewaehlte Basis: `index-14-white.html`
- Grund fuer die Auswahl:
  - One-Page-Aufbau mit bereits vorhandenen Anchor-Navigationen.
  - Klare Hero-, Service- und Kontaktstruktur als gute Grundlage fuer eine Conversion-Landingpage.
  - White-Variante passt besser zu einem serioesen B2B-Auftritt.

## Umsetzung im Projekt
- Zielseite fuer GitHub Pages auf `index.html` umgesetzt.
- Sprache und SEO angepasst:
  - `lang="de"`
  - neuer Seitentitel
  - neue Meta Description
  - grundlegende Open-Graph-Metadaten
- Navigation zu einer One-Page-Navigation auf die neuen Sektionen umgebaut.
- Irrelevante Portfolio-/Resume-/Blog-/Pricing-/Demo-Elemente entfernt.
- Verbindliche Zielreihenfolge der Sektionen umgesetzt:
  1. Hero
  2. Typische Herausforderungen in Unternehmen
  3. Power Platform Loesungen
  4. Ihre Vorteile mit einem Freelancer
  5. Beispiel-Projekte / Use Cases
  6. Projektablauf
  7. Ueber mich
  8. Call to Action
  9. Kontaktformular
- Formular auf statische Nutzung vorbereitet (GitHub Pages kompatibel) und im HTML kommentiert, wo Formspree/Netlify anzuschliessen ist.
- Telefonnummer als alternative Conversion prominent in Hero, CTA und Kontaktbereich eingebunden.
- Kleine lokale CSS-Ergaenzungen in `index.html` fuer Lesbarkeit, Abstaende und Card-Konsistenz.

## Technische Aufraeumarbeiten
- Stark template-spezifische Showcase-/Demo-Bloecke aus `index.html` entfernt.
- Interne Ankerziele und Navigation aufeinander abgestimmt.
- Seite bleibt statisch und ohne zusaetzliches Framework.
