# mockup-contacto.fig.md

Frame: ContactSection
Viewport: mobile-first
Layout:
  direction: vertical
  padding: 24px
  gap: 20px
Content:
  - Header:
      status: "Tiempo de respuesta habitual: < 24h"
      heading: "¿Hablamos sobre lo que necesitas?"
      subheading: "Atención presencial en Madrid (Arturo Soria) y también online."
  - TwoColumnGrid:
      columns: 1 (mobile), 2 (desktop)
      gap: 20px
      items:
        - LeftColumn:
            title: "Formulario de contacto"
            form:
              fields:
                - name: "Nombre *"
                  type: "text"
                - email: "Email *"
                  type: "email"
                - phone: "Teléfono (opcional)"
                  type: "tel"
                - message: "Mensaje *"
                  type: "textarea"
              privacy_checkbox:
                required: true
                text: "He leído y acepto la política de privacidad"
              submit_button:
                text: "Enviar mensaje"
                width: "full"
                state: "disabled_by_default"
                enabled_when: "all_fields_valid_and_privacy_checked"
                validation:
                  - nombre: "required"
                  - email: "required_and_valid"
                  - mensaje: "required"
                  - privacy_checkbox: "required"
              security_note:
                text: "Tus datos se envían de forma segura."
                position: "below_button"
        - RightColumn:
            title: "Datos de contacto"
            contact_info:
              - phone: "+34 610 576 297"
                href: "tel:+34610576297"
              - email: "bycpsicologia@gmail.com"
                href: "mailto:bycpsicologia@gmail.com"
              - address: "Calle Arturo Soria 144, 28043 Madrid"
            map:
              source: "Google Maps iframe"
              height: 250
              width: full
            social_media:
              heading: "También estoy en:"
              links:
                - name: "LinkedIn"
                  href: "https://www.linkedin.com/in/beatriz-corchado-93a913282/"
                  color: "blue"
                - name: "Doctoralia"
                  href: "https://www.doctoralia.es/beatriz-corchado-de-frutos/psicologo/madrid"
                  color: "green"
                - name: "Instagram"
                  href: "https://www.instagram.com/byc_psicologia/"
                  color: "pink"
                - name: "Colegio Oficial de la Psicología de Madrid"
                  src: "assets/icons/colegio-psicologia-madrid.png"
                  href: "https://www.copmadrid.org/web/ciudadania/detalle-profesional/M-40164/BEATRIZ-YOLANDA-CORCHADO-DE-FRUTOS"
                  color: "green"


  - SuccessOverlay:
      title: "¡Mensaje enviado!"
      message: "Me pondré en contacto contigo lo antes posible, gracias."
      button: "Cerrar"
Theme:
  colors: use-existing
  font: use-existing
  card-style: white-bg-border
  button-style: sage-bg