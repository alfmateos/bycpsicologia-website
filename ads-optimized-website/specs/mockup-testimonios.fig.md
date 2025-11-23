# mockup-testimonios.fig.md

Frame: TestimonialsSection
Layout:
  direction: vertical
  padding: 24px
  gap: 16px
Content:
  - Heading: "Opiniones"
  - Carousel:
      type: "testimonials"
      items:
        - Card:
            rating: 5
            stars: "★★★★★"
            text: "Muy profesional y cercana. Me ayudó a manejar la ansiedad en el postparto desde la primera sesión."
            author: "Patricia García, 33 años"
            topic: "Psicología perinatal"
        - Card:
            rating: 5
            stars: "★★★★★"
            text: "Un acompañamiento profesional cuando más lo necesitaba. Beatriz me ayudó a superar un momento muy difícil."
            author: "María López, 35 años"
            topic: "Terapia individual"
        - Card:
            rating: 5
            stars: "★★★★★"
            text: "Tras la pérdida de nuestro bebé, Beatriz nos ayudó a procesar el duelo como pareja. Su empatía y profesionalidad fueron fundamentales."
            author: "Carlos Martínez, 38 años"
            topic: "Duelo gestacional y terapia de pareja"
        - Card:
            rating: 5
            stars: "★★★★★"
            text: "Llevaba años con ansiedad sin saber cómo gestionarla. Con Beatriz aprendí herramientas prácticas que realmente funcionan en mi día a día."
            author: "Elena Rodríguez, 42 años"
            topic: "Terapia individual - Ansiedad"
        - Card:
            rating: 5
            stars: "★★★★★"
            text: "Mi pareja y yo estábamos en crisis. Las sesiones de terapia de pareja con Beatriz nos ayudaron a comunicarnos mejor y recuperar la conexión."
            author: "Sofía y David Fernández, 40 y 41 años"
            topic: "Terapia de pareja"
        - Card:
            rating: 5
            stars: "★★★★★"
            text: "Como madre primeriza, me sentía perdida. Beatriz me ayudó a entender mis emociones y a confiar en mi instinto maternal. Muy recomendable."
            author: "Laura Sánchez, 29 años"
            topic: "Psicología perinatal - Maternidad"
        - Card:
            rating: 5
            stars: "★★★★★"
            text: "Excelente profesional. Me ayudó a trabajar mi autoestima y a superar bloqueos emocionales que llevaba años arrastrando. Totalmente recomendado."
            author: "Javier Ruiz, 36 años"
            topic: "Terapia individual - Autoestima"
      navigation:
        - prev_button: "Anterior"
        - next_button: "Siguiente"
        - touch_swipe: "Deslizar con el dedo (móvil)"
      indicators:
        - dots: true
        - count: 7
Theme:
  colors: use-existing
  card-style: white-border
  button-style: sage-bg
