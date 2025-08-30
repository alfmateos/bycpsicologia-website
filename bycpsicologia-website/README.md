# Página Web - Psicóloga Beatriz Corchado

Este es el código fuente de la página web de la psicóloga Beatriz Corchado, adaptado desde la plantilla original de https://www.psicologanoelia.es

## Estructura del Proyecto

```
psicologanoelia-website/
├── index.html                 # Página principal
├── styles-W7ZQXRS5.css        # Estilos CSS
├── main-FXPKFYCL.js          # JavaScript principal (Angular)
├── polyfills-FFHMD2TL.js     # Polyfills para compatibilidad
├── favicon.ico               # Icono del sitio
├── assets/                   # Recursos estáticos
│   ├── logo/
│   │   └── logo.png          # Logo de la psicóloga
│   ├── images/
│   │   ├── hero.png          # Imagen de fondo del hero
│   │   ├── noelia_circle.png # Foto de perfil
│   │   └── desk.jpg          # Imagen del escritorio
│   └── icons/
│       ├── separador.svg     # Separador decorativo
│       ├── menu.svg          # Icono del menú
│       ├── heart.svg         # Icono de corazón
│       ├── check.svg         # Icono de verificación
│       ├── star.svg          # Icono de estrella
│       └── instagram.svg     # Icono de Instagram
└── README.md                 # Este archivo
```

## Tecnologías Utilizadas

- **Angular 18.2.12**: Framework principal
- **Tailwind CSS**: Framework de estilos CSS
- **HTML5**: Estructura semántica
- **TypeScript/JavaScript**: Lógica de la aplicación

## Cómo Ejecutar el Proyecto Localmente

### Opción 1: Servidor HTTP Simple (Recomendado para visualización)

1. Abre una terminal y navega al directorio del proyecto:
   ```bash
   cd psicologanoelia-website
   ```

2. Inicia un servidor HTTP local usando Python:
   ```bash
   python3 -m http.server 8000
   ```

3. Abre tu navegador web y ve a:
   ```
   http://localhost:8000
   ```

### Opción 2: Usando Node.js (si tienes npm instalado)

1. Instala un servidor HTTP global:
   ```bash
   npm install -g http-server
   ```

2. Navega al directorio del proyecto:
   ```bash
   cd psicologanoelia-website
   ```

3. Inicia el servidor:
   ```bash
   http-server -p 8000
   ```

4. Abre tu navegador web y ve a:
   ```
   http://localhost:8000
   ```

### Opción 3: Usando Live Server (VS Code)

Si usas Visual Studio Code:

1. Instala la extensión "Live Server"
2. Abre el proyecto en VS Code
3. Haz clic derecho en `index.html`
4. Selecciona "Open with Live Server"

## Características de la Página

- **Diseño Responsivo**: Se adapta a dispositivos móviles y desktop
- **Navegación Suave**: Enlaces internos con scroll suave
- **Secciones Principales**:
  - Hero con llamada a la acción
  - Sobre mí (información personal)
  - Servicios ofrecidos
  - Tarifas (sesión individual y bono de 4 sesiones)
  - Reseñas de clientes
  - Información de contacto
- **SEO Optimizado**: Meta tags y datos estructurados
- **Accesibilidad**: Estructura semántica y alt texts

## Contacto

- **Email**: bycpsicologia@gmail.com
- **Teléfono**: 610 576 297
- **Especialidades**: Psicología perinatal, terapia familiar, acompañamiento en cambios vitales

## Notas Técnicas

- La aplicación está construida con Angular y compilada para producción
- Los archivos JavaScript están minificados
- Se utiliza Tailwind CSS para los estilos
- La página es una SPA (Single Page Application) con navegación por fragmentos
