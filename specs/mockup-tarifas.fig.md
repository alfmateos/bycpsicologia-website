# mockup-tarifas.fig.md

Frame: PricingSection
Viewport: mobile-first
Layout:
  direction: vertical
  padding: 24px
  gap: 20px
Content:
  - Heading:
      level: h2
      text: "Tarifas"
  - Grid:
      columns: 1 (mobile), 2 (desktop)
      gap: 20px
      items:
        - PricingCard:
            title: "SSesión Informativa"
            price: "Gratuita"
            items:
              - "30 minutos aprox."
              - "Telefónica"
            button:
              text: "Quiero reservar"
              href: "tel:+34610576297"      
        - PricingCard:
            title: "Sesión Individual"
            price: "60€"
            items:
              - "55 minutos aprox."
              - "Presencial u online"
            button:
              text: "Quiero reservar"
              href: "tel:+34610576297"
        - PricingCard:
            title: "Bono de 4 sesiones"
            price: "200€"
            items:
              - "55 minutos aprox. cada sesión"
              - "Presencial u online"
            button:
              text: "Quiero reservar"
              href: "tel:+34610576297"
  - Footer:
      text: "¿Colectivos vulnerables? Pregúntame por precios especiales"
      size: large
      weight: semibold
Theme:
  colors: use-existing
  font: use-existing
  card-style: white-bg-shadow-rounded
  price-color: primary
  button-style: sage-bg
