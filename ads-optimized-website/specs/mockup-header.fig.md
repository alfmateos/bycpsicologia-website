# mockup-header.fig.md

Frame: Header
Viewport: mobile-first and desktop
Position: fixed
Background: white with dynamic opacity
  - Initial (no scroll): bg-opacity-0, backdrop-blur-0
  - On scroll (>50px): bg-opacity-95, backdrop-blur-md, shadow-md
Z-index: 50
Transition: all 300ms
Layout:
  direction: horizontal
  justify: space-between
  align: center
  padding: 8px-16px (mobile and desktop)
Children:
  - Logo:
      source: "assets/logo/logo-3.png"
      height: 44px (same as Contact button)
      width: auto
      border-radius: 8px
      margin-right: 32px

  - DesktopNavigation (hidden on mobile, visible on lg):
      direction: horizontal
      gap: 32px
      items:
        - Link:
            text: "Inicio"
            href: "#hero"
            color: "off-white"
            hover: "gray-300"
        - Link:
            text: "Para quién"
            href: "#for-whom"
            color: "off-white"
            hover: "gray-300"
        - Link:
            text: "Servicios"
            href: "#services"
            color: "off-white"
            hover: "gray-300"
        - Link:
            text: "Sobre mí"
            href: "#about"
            color: "off-white"
            hover: "gray-300"
        - Link:
            text: "Tarifas"
            href: "#pricing"
            color: "off-white"
            hover: "gray-300"
        - Link:
            text: "Opiniones"
            href: "#testimonials"
            color: "off-white"
            hover: "gray-300"

  - Actions:
      direction: horizontal
      gap: 16px
      margin-left: auto
      items:
        - WhatsAppButton:
            icon: true
            href: "https://wa.me/34610576297"
            target: "_blank"
            size: "40px (mobile), 48px (desktop)"
            background: "green-500"
            hover: "green-600"

        - ContactButton (hidden on mobile, visible on lg):
            text: "Contacto"
            href: "#contact"
            background: "sage"
            hover: "primary"
            padding: "12px 24px"
            border-radius: "8px"

        - MobileMenu (visible on mobile, hidden on lg):
            button:
              id: "mobile-menu-btn"
              icon: "assets/icons/menu.svg"
              size: "32px"
            dropdown:
              id: "mobile-menu"
              position: "absolute right-0 mt-2"
              width: "224px"
              background: "white"
              border-radius: "8px"
              shadow: "lg"
              items:
                - Link:
                    text: "Inicio"
                    href: "#hero"
                - Link:
                    text: "Para quién"
                    href: "#for-whom"
                - Link:
                    text: "Servicios"
                    href: "#services"
                - Link:
                    text: "Sobre mí"
                    href: "#about"
                - Link:
                    text: "Tarifas"
                    href: "#pricing"
                - Link:
                    text: "Opiniones"
                    href: "#testimonials"
                - Link:
                    text: "Contacto"
                    href: "#contact"
                - WhatsAppLink:
                    text: "WhatsApp"
                    href: "https://wa.me/34610576297"
                    target: "_blank"
                    icon: true

Theme:
  colors: use-existing
  fonts: use-existing
  header-background: "transparent"
  text-color: "off-white (desktop), brown-dark (mobile menu)"
