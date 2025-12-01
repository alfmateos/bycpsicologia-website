# 07-rules-and-restrictions.md
## Reglas técnicas OBLIGATORIAS para index-ads-optimized.html
Estas reglas son estrictas y deben cumplirse en toda la implementación.

---

## 1. Prohibido usar acortadores (bit.ly, tinyurl, rebrand.ly)
- No se permiten acortadores de ningún tipo.
- Solo URL completas y oficiales.

Correcto:
https://wa.me/34610576297?text=Hola%20Beatriz

Incorrecto:
https://bit.ly/3abcxyz

---

## 2. WhatsApp: usar EXCLUSIVAMENTE wa.me
Formato obligatorio (URL-encoded):
https://wa.me/34610576297?text=Hola%20Beatriz%2C%20me%20gustaría%20información

Prohibido:
- api.whatsapp.com
- wa.link
- acortadores

---

## 3. Teléfono: usar siempre tel:+34XXXXXXXXX (formato E.164)
Formato obligatorio:
<a href="tel:+34610576297">

Prohibido:
- javascript:window.open("tel:...")
- onclick="..."
- href="tel:610576297"

---

## 4. Mantener logo, colores y tipografías EXACTAMENTE como en index.html
- Extraer colores del CSS actual o inline styles existentes.
- No inventar paletas nuevas.
- No sustituir tipografías por Google Fonts nuevas.
- No cambiar el logo ni su proporción.

---

## 5. NUNCA modificar index.html
- El nuevo archivo es totalmente independiente.
- No sobrescribir ni mezclar contenido.
- No extraer partes dinámicas a menos que se copien explícitamente.

---

## 6. Sin JavaScript externo innecesario
Prohibido:
- jQuery (si no existe ya)
- Bootstrap (si no existe ya)
- Material UI
- Cualquier librería grande que aumente peso

Landing debe funcionar con:
- HTML
- CSS actual o nuevo CSS ligero
- JS mínimo o ninguno

---

## 7. Sin popups, modales ni banners intrusivos
Prohibido:
- Popups full-screen
- Ventanas emergentes automáticas
- Banners que bloqueen la interacción
- Popups que salten tras X segundos

---

## 8. Optimización móvil OBLIGATORIA
- Botones a 100% del ancho
- Iconos suficientemente grandes
- Nada que requiera zoom
- Textos con line-height adecuado

---

## 9. Formulario accesible y simple
Campos:
- name
- email
- message

Requisitos:
- Labels visibles (no placeholders como etiquetas)
- autocomplete activo
- No añadir captcha salvo necesidad legal
- Sin JS obligatorio para enviar

---

## 10. Enlaces internos con scroll normal
Prohibido:
- scroll-behavior: smooth aplicado indiscriminadamente
- librerías smooth-scroll
- animaciones JS de scroll

---

## 11. Imágenes
- Comprimir ≤120 KB siempre que sea posible
- Mantener proporciones del sitio original
- Usar formatos web-friendly (webp si se quiere, pero opcional)

---

## 12. HTML semántico mínimo obligatorio
Debe incluir:
- <header>
- <main>
- <section>
- <footer>

---

## 13. No añadir tracking adicional sin consentimiento
Prohibido añadir:
- Facebook Pixel
- Hotjar
- Scripts de terceros no esenciales

Google Ads ya gestiona su auto-tagging.

---

## 14. Barra flotante móvil OBLIGATORIA
- position: fixed
- bottom: 0; left: 0; right: 0;
- Dos botones:
  - Llamar
  - WhatsApp
- Prohibido usar JS para fijarla

---

## 15. URLs de WhatsApp deben ir correctamente URL-encoded
Correcto:
https://wa.me/34610576297?text=Hola%20Beatriz%2C%20me%20gustaría%20información

Incorrecto:
https://wa.me/34610576297?text=Hola Beatriz, me gustaría información

---

## 16. Código limpio obligatorio
- Evitar estilos inline salvo casos mínimos y controlados
- CSS organizado en bloques
- No duplicar reglas
- No crear clases sin usar

---

## 17. Seguridad básica
- No exponer direcciones de email dentro de JS
- No usar formularios que dependan únicamente de JS para enviar
- No almacenar información sensible del usuario en el HTML
