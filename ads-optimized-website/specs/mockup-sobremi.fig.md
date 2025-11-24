# mockup-sobremi.fig.md

Frame: AboutSection
Position: Second section (after Hero, before Para quién)
Layout:
  mobile:
    direction: vertical
    padding: 24px
    gap: 20px
    align: center
    background: white
  desktop:
    direction: horizontal
    columns: 2
    gap: 48px
    align: center
    max-width: 6xl
    padding: 48px
    background: white
Content:
  - Mobile: Heading: "Sobre mí"
  - Mobile: Photo:
      source: existing
      maxWidth: 160px
      shape: rounded-full
  - Desktop: LeftColumn:
      Photo:
        source: existing
        height: 500px
        shape: rounded-lg
        shadow: lg
  - Desktop: RightColumn:
      Heading: "Sobre mí"
  - Paragraph: "Soy Beatriz Corchado, psicóloga graduada por la UNED y Máster en Psicología General Sanitaria por la UNIR."
  - Paragraph: "Además poseo el título de Experto en Psicología Perinatal por la UNIR, Experto en Reducción del Estrés Basado en el Mindfulness (MBSR) y Experto en Orientación Psicológica e Intervención en Crisis en Niños y Adolescentes en Riesgo."
  - Paragraph: "Poseo experiencia en intervención en familias vulnerables, en situaciones de violencia y desarraigo y monoparentales."
  - Paragraph: "Antes de la psicología, mi gran vocación fue la maternidad. Tengo tres hijos jóvenes que me enseñaron que ser madre es una experiencia transformadora para la que nadie nos prepara realmente." 
  - Paragraph: "Hoy, mi propósito es escucharte, acompañarte y ayudarte a atravesar los cambios y dificultades que puedas estar experimentando."
  - Paragraph: "Trabajo desde un enfoque integrador, respetuoso y basado en la evidencia."
  - Microcopy: "Cuando quieras, estoy disponible para escucharte."
   - CTARow:
      direction: "flex-col sm:flex-row"
      gap: 12px
      items:
          - ButtonPrimary:
              text: "Llamar"
              href: "tel:+34610576297"
          - ButtonSecondary:
              text: "WhatsApp"
              href: "https://wa.me/34610576297?text=Hola%20Beatriz%2C%20me%20gustaría%20más%20información"
Theme:
  colors: use-existing
  fonts: use-existing
