Quiero que generes una única página HTML completa llamada:

    index-ads-optimized.html

y que la guardes en el directorio:

    ads-optimized-website/

NO debes alterar ni sobreescribir la página existente index.html del proyecto.

La nueva landing debe construirse EXACTAMENTE siguiendo todas las especificaciones que te adjunto en los siguientes ficheros markdown:

ads-optimized-website/specs/01-overview.md  
ads-optimized-website/specs/02-layout-structure.md  
ads-optimized-website/specs/03-content-copy.md  
ads-optimized-website/specs/04-styles-theming.md  
ads-optimized-website/specs/05-behaviour-ctas.md  
ads-optimized-website/specs/06-technical-notes.md  
ads-optimized-website/specs/07-rules-and-restrictions.md  
ads-optimized-website/specs/08-tailwind-guidelines.md  

y todos los mockups Figma-like:

ads-optimized-website/specs/mockup-*.fig.md

INSTRUCCIONES OBLIGATORIAS PARA TI:

1. NO inventes nada que no esté en los .md.  
2. La landing debe ser mobile-first, optimizada para máxima conversión (llamada y WhatsApp).  
3. Usa EXCLUSIVAMENTE Tailwind CSS siguiendo 08-tailwind-guidelines.md.  
4. Reutiliza colores, tipografías, spacing y branding del index.html original.  
5. Asegúrate de que el Tailwind Purge funciona incluyendo esta nueva página.  
6. Los CTAs principales deben ser llamar y WhatsApp con formato correcto:
   - Teléfono: tel:+34610576297
   - WhatsApp: https://wa.me/34610576297?text=... (URL-encoded)
7. Prohibido usar:
   - ONCLICK en CTAs
   - javascript:window.open(...)
   - api.whatsapp.com
   - bit.ly u otros acortadores
   - Bootstrap, Material, DaisyUI, Flowbite o cualquier otra UI library
8. Debes incluir:
   - El mismo mecanismo POST del formulario del index.html original (action + method + field names).
   - Mapa de ubicación debajo del formulario usando el mismo iframe usado en index.html.
   - Footer con iconos de Instagram, Doctoralia y LinkedIn.
9. Debes respetar TODAS las reglas del archivo 07-rules-and-restrictions.md.
10. El resultado debe ser:
    - Un único archivo HTML listo para producción,
    - sin dependencias adicionales,
    - con estructura semántica correcta (<header>, <main>, <section>, <footer>),
    - con botones enormes, claros y accesibles en móvil.

TU OUTPUT:
Devuélveme únicamente el contenido completo del archivo:

    ads-optimized-website/index-ads-optimized.html

en código HTML listo para copiar/pegar.
No generes notas ni explicaciones fuera del código.