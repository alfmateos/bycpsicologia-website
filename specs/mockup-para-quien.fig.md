# mockup-para-quien.fig.md

Frame: ForWhomSection
Viewport: mobile-first and desktop
Layout:
  mobile:
    direction: vertical
    padding: 24px
    gap: 16px
  desktop:
    direction: horizontal
    columns: 2
    gap: 48px
    align: center
    max-width: 6xl
    padding: 32px
Content:
  - LeftColumn:
      items:
        - Heading:
            text: "¿Te sientes identificada con alguna de estas situaciones?"
            size: "4xl"
            weight: "normal"
            font: "Roboto"
            tracking: "wide"
            text-align: "center"
        - BulletList:
            gap: 16px
            items:
              - Sientes ansiedad, preocupación o tristeza durante la preconcepción, el embarazo o postparto.
              - Te cuesta adaptarte a tu nueva etapa como madre.
              - Tienes dificultades para dormir o desconectar mentalmente.
              - Te sientes sola, desbordada o culpable.
              - Has vivido una pérdida gestacional o parto traumático.
              - Tu relación de pareja se ha resentido desde que llegó el bebé.
              - La relación con tus hijos adolescentes se ha vuelto insoportable.
        - Microcopy:
            text: "Da el primer paso: no tienes que hacerlo sola."
            weight: "semibold"
            align: "center"
        - CTARow:
            direction: "flex-col sm:flex-row"
            gap: 12px
            justify: "center"
            items:
              - ButtonPrimary:
                  text: "Llamar"
                  href: "tel:+34610576297"
              - ButtonSecondary:
                  text: "WhatsApp"
                  href: "https://wa.me/34610576297?text=Hola%20Beatriz%2C%20me%20gustaría%20más%20información"

  - RightColumn (desktop only):
      image:
        src: "assets/images/mother-child-back.jpg"
        alt: "Madre e hijo"
        height: "500px"
        border-radius: "8px"
        shadow: "lg"
        object-fit: "cover"

Theme:
  colors: use-existing
  fonts: use-existing
  background: "white"
