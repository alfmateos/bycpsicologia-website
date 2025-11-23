# 08-tailwind-guidelines.md
## Uso obligatorio de Tailwind CSS en index-ads-optimized.html

La landing page `index-ads-optimized.html` debe utilizar Tailwind CSS,
reutilizando la configuración existente en el proyecto original y sin introducir nuevas librerías CSS o JS.

---

## 1. Reutilizar la instalación de Tailwind existente
- Usar exactamente la instalación y configuración de Tailwind ya presente en el proyecto.
- No crear una instalación nueva.
- No añadir nuevas paletas de colores, fuentes o valores que no existan en `tailwind.config.js`.
- Mantener la identidad visual del sitio (colores, tipografías, espaciados).

### Requisito obligatorio de purge/content
En `tailwind.config.js`, incluir `index-ads-optimized.html` dentro de `content`:

```js
content: [
  "./index.html",
  "./index-ads-optimized.html",
  "./**/*.js",
  "./**/*.php",
]
```   

## 4. Pautas de uso de Tailwind para la nueva landing

### 4.1 Hero / Primera pantalla
	•	Padding: py-10 px-4
	•	Título: text-2xl font-semibold leading-tight
	•	Subtítulo: text-base text-gray-700 leading-relaxed
	•	Botones CTA:
	•	Comunes: w-full py-3 font-semibold rounded-md text-center
	•	Llamada: usar el color de acento original (bg-[color] text-white)
	•	WhatsApp: borde o tono claro del color de acento

### 4.2 Secciones
	•	Separación vertical: py-10 md:py-16
	•	Contenedor: max-w-screen-md mx-auto px-4

### 4.3 Listas (“Problemas que resuelvo”, etc.)
	•	space-y-3
	•	Items: flex items-start gap-2
	•	Bullet o icono: tamaño discreto (clase recomendada: w-4 h-4 mt-1)

### 4.4 Servicios
	•	Grid en desktop: grid gap-6 md:grid-cols-2
	•	Card: p-6 rounded-lg shadow-sm bg-white

### 4.5 Sobre mí
	•	Foto: w-32 h-32 rounded-full mx-auto mb-6
	•	Texto: text-base leading-relaxed space-y-4

### 4.6 Tarifas
	•	Título o cifra importante: text-lg font-semibold
	•	Espaciado: space-y-3

### 4.7 Testimonios
	•	Card testimonial: p-4 rounded-lg bg-gray-50 shadow-sm
	•	Texto: leading-relaxed text-sm

### 4.8 Formulario de contacto
	•	Inputs:
	•	w-full p-3 border rounded-md
	•	Textarea:
	•	w-full p-3 border rounded-md min-h-[120px]
	•	Botón enviar:
	•	w-full py-3 font-semibold rounded-md bg-[color_acento] text-white

### 4.9 Mapa
	•	Contenedor: mt-6
	•	Iframe: w-full h-64 rounded-md

### 4.10 Footer (iconos de redes)
	•	Contenedor: flex items-center justify-center gap-4 py-6
	•	Iconos: w-6 h-6

⸻

## 5. Reglas estrictas de estilo con Tailwind
	•	Prohibido usar estilos inline salvo casos extremadamente justificados.
	•	Prohibido crear un archivo CSS adicional con estilos duplicados.
	•	Prohibido usar clases Tailwind inexistentes en la configuración original.
	•	Estructura recomendada: composición de utilidades claras, sin anidar excesivamente.

⸻

## 6. Objetivo final del uso de Tailwind

Tailwind debe permitir:
	•	Una landing muy profesional y visualmente pulida.
	•	Rapidísima implementación (AI-friendly).
	•	Legibilidad excelente en móvil.
	•	Botones prominentes para maximizar llamadas y WhatsApps.
	•	Consistencia visual con el sitio original.
	•	Menor peso final gracias al purge correcto.