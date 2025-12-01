# 02-layout-structure.md

## Orden definitivo de secciones (mobile-first)

1. **Header compacto**
   - Logo (misma imagen del proyecto original)
   - Accesos rápidos: WhatsApp + Teléfono
   - Sin redes sociales
   - Sin menú
   - Sin textos largos

2. **HERO (orientado totalmente a la conversión)**
   - Título claro profesional
   - Subtítulo directo sobre especialización
   - Credenciales sanitarias visibles
   - CTA 1: Llamar ahora (primario)
   - CTA 2: WhatsApp (secundario)
   - Nota opcional: “Primera llamada informativa sin coste”
   - Debajo: “Sesiones presenciales en Arturo Soria y online”

3. **¿Para quién es este servicio?**
   - Sección corta y decisiva.
   - Lista de situaciones comunes:
     - ansiedad embarazo o postparto,
     - tristeza, culpa, desbordamiento,
     - adaptación difícil a maternidad,
     - problemas de sueño,
     - duelo gestacional,
     - conflictos de pareja.
   - CTA breve: Llamar / WhatsApp

4. **Servicios (En qué puedo ayudarte)**
   - 4 bloques tipo “card”, tailwind-friendly:
     - Embarazo
     - Postparto
     - Duelo gestacional
     - Terapia individual / pareja
   - Cada card incluye título + descripción sanitaria y concisa.

5. **Cómo son las sesiones**
   - Explicación clara del proceso:
     - Primera llamada gratuita informativa
     - Duración sesiones: 55 min
     - Modalidad: online o presencial en Arturo Soria
     - Enfoque personalizado
     - Herramientas prácticas para el día a día
   - CTA discreto: “Reservar llamada”

6. **Sobre mí (versión optimizada breve)**
   - Foto circular (misma del proyecto)
   - Título: “Sobre mí”
   - Texto conciso profesional:
     - Psicóloga Sanitaria especializada en maternidad y salud perinatal.
     - Enfoque basado en evidencia, cercano y respetuoso.
   - Credenciales:
     - Psicóloga Sanitaria M-40164
     - Especialista en salud perinatal
     - Atención presencial y online

7. **Testimonios**
   - 2–3 opiniones breves verificadas.
   - Formato card o bloque simple.

8. **Tarifas claras**
   - Sesión individual: 60 €
   - Sesión de pareja: 70 €
   - Nota: “Si no sabes qué tipo de sesión necesitas, lo vemos juntas en la llamada gratuita.”
   - CTA: Llamar ahora

9. **Contacto directo**
   - Teléfono
   - WhatsApp
   - Formulario (nombre, email, mensaje)
   - Política de datos
   - Mapa (mismo iframe que index.html)

10. **Barra flotante (solo móvil)**
    - Botón “Llamar”
    - Botón “WhatsApp”
    - Siempre visible (CSS fixed)
    - Nunca usar JS para fijarla

## Elementos que deben integrarse desde index.html original

### Mapa
- Colocar debajo del formulario de contacto.
- Usar el MISMO iframe o código exacto de index.html.
- No cargar Google Maps API nueva.

### Redes profesionales
- Solo en el footer:
  - Instagram
  - Doctoralia
  - LinkedIn
- Iconos discretos (24px)
- Sin textos largos

### Formulario POST (backend existente)
El formulario debe usar **el mismo endpoint POST y los mismos field names que index.html**
para asegurar compatibilidad con el backend actual.