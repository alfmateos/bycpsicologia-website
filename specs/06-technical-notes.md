# 06-technical-notes.md

## Archivo final
Crear: index-ads-optimized.html  
No modificar index.html.

## Semántica
<header>
<main>
<section>
<footer>

## Performance
- No js innecesario
- Minimizar peso de imágenes

## Accesibilidad mínima
- Labels en inputs
- Alt en imágenes
- Botones con contraste

## NOTAS
- Prohibido añadir jQuery si no existe
- Prohibido añadir Bootstrap, Material UI, frameworks UI
- Landing debe funcionar con HTML + CSS + mínimo JS
- Prohibido añadir scripts de tracking sin consentimiento
- Prohibido añadir smooth-scroll JS

## Mapa
- Integrar usando exactamente el iframe o código del index.html original.
- Si el mapa se carga mediante JS externo en index.html, copiar el mismo mecanismo.
- Prohibido cargar Google Maps API completa si no está en el original.
- Colocarlo debajo del formulario.

## Formulario POST
- Debe usar el mismo action y method del formulario original.
- Debe respetar los mismos field names.
- No añadir validación JS invasiva.
- Debe funcionar con HTML puro.

## Redes sociales
- Colocar únicamente en el footer.
- No usar JS dinámico ni widgets pesados (p.ej., embebidos de Instagram).
- Usar enlaces simples con iconos SVG o PNG ligeros.