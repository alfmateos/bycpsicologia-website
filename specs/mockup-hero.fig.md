# mockup-hero.fig.md

Frame: HeroSection
Viewport: mobile-first and desktop
Layout:
  mobile:
    direction: vertical
    padding-top: 0
    padding-bottom: 24px
    padding-left: 16px
    padding-right: 16px
    gap: 16px
    align: center
    background:
      image: "assets/images/hero-section-background.png"
      size: "cover"
      position: "center"
      repeat: "no-repeat"
  desktop:
    direction: horizontal
    padding-top: 0
    padding-bottom: 48px
    padding-left: 0
    padding-right: 0
    background:
      image: "assets/images/hero-section-background-wide.png"
      size: "cover"
      position: "center"
      repeat: "no-repeat"
    min-height: 700px
    align: center
    justify: flex-end
    padding-right: 48px
    max-width: full
    content-max-width: "max-w-lg"
Content:
  - RightColumn (desktop only):
      align: center
      gap: 24px
      vertical-align: center
      padding: 80px 0
      max-width: 448px
      items:
        - H1:
            text: "Beatriz Corchado Psicología"
            font: "Roboto"
            size: "4xl"
            weight: "normal"
            tracking: "wide"
        - H2:
            text: "Consulta en Madrid y Online"
            size: "2xl-3xl"
            weight: "semibold"
        - Paragraphs:
            text: "Acompañamiento psicológico en maternidad, infertilidad, menopausia, cambios vitales y terapia familiar. Un espacio seguro para tu bienestar emocional."
            text: "Si te encuentras en momentos de ansiedad, dudas, agotamiento emocional o duelo, juntas encontraremos recursos para que te sientas mejor."
            size: "lg-xl"
        - Credentials:
            items:
              - "Cuéntame qué necesitas"
            size: "sm-base"
        - ButtonGroup:
            layout: "flex-col sm:flex-row"
            gap: 12px
            justify: "center"
            items:
              - ButtonPrimary:
                  text: "Llamar ahora"
                  href: "tel:+34610576297"
              - ButtonSecondary:
                  text: "WhatsApp"
                  href: "https://wa.me/34610576297"
Theme:
  colors: use-existing
  font: use-existing
