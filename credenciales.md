# 🔐 Credenciales - bycpsicologia.com

## 📋 Información General

**Proyecto**: bycpsicologia-website  
**Repositorio**: https://github.com/alfmateos/bycpsicologia-website  
**Sitio en Producción**: https://bycpsicologia.com  
**Directorio Local**: `/Users/alfonso/bycpsicologia`

---

## 🔑 GitHub

### Acceso al Repositorio
- **URL**: https://github.com/alfmateos/bycpsicologia-website
- **Rama Principal**: `main`
- **Autenticación**: SSH (configurada localmente)

### Comandos Útiles
```bash
# Clonar el repositorio
git clone git@github.com:alfmateos/bycpsicologia-website.git

# Ver tags disponibles
git tag -l

# Crear un nuevo tag
git tag -a "release-nombre-1.0" -m "Descripción del release"
git push origin "release-nombre-1.0"

# Ver commits recientes
git log --oneline -10
```

---

## 🚀 Netlify

### Información del Sitio
- **Nombre del Sitio**: bycpsicologia-staging
- **URL de Producción**: https://bycpsicologia.com
- **Account ID**: 688486be886b697a14d709f6
- **Directorio de Deploy**: `bycpsicologia-website`

### Autenticación Netlify
- **Método**: CLI con token (configurado localmente)
- **Token**: Almacenado en `~/.netlify/state.json`

### Comandos de Deploy
```bash
# Deploy a producción
netlify deploy --prod --dir=bycpsicologia-website

# Ver estado del deploy
netlify status

# Ver logs del deploy
netlify logs
```

---

## 📁 Estructura del Proyecto

```
bycpsicologia/
├── bycpsicologia-website/
│   ├── index.html (archivo principal)
│   ├── politica-privacidad.html
│   ├── sitemap.xml
│   ├── assets/
│   │   ├── logo/
│   │   │   ├── logo-3.png (favicon actual)
│   │   │   ├── logo-2.png
│   │   │   └── logo-4-largo.png
│   │   ├── images/
│   │   ├── videos/
│   │   ├── icons/
│   │   └── fonts/
│   └── .gitignore
├── .git/
└── README.md
```

---

## 🔄 Flujo de Trabajo Típico

### 1. Hacer cambios locales
```bash
cd /Users/alfonso/bycpsicologia
# Editar archivos en bycpsicologia-website/
```

### 2. Commit y Push a GitHub
```bash
git add -A
git commit -m "Descripción del cambio"
git push
```

### 3. Deploy a Netlify (Producción)
```bash
netlify deploy --prod --dir=bycpsicologia-website
```

### 4. Crear un Release (opcional)
```bash
git tag -a "release-nombre-X.X" -m "Descripción"
git push origin "release-nombre-X.X"
```

---

## 📊 Información Importante

### Favicon
- **Archivo**: `/assets/logo/logo-3.png`
- **Configuración**: Definida en `<head>` del `index.html`
- **No usar**: `favicon.ico` (eliminado)

### Formulario de Contacto
- **Servicio**: Formspree
- **ID del Formulario**: `xvgwzbal`
- **URL**: `https://formspree.io/f/xvgwzbal`
- **Email destino**: `bycpsicologia@gmail.com`

### Google Analytics
- **ID de Seguimiento**: `G-YS6KBTNR3X`
- **Configurado en**: `<head>` del `index.html`

### Google Search Console
- **URL**: https://search.google.com/search-console
- **Propiedad**: bycpsicologia.com
- **Sitemap**: https://bycpsicologia.com/sitemap.xml

---

## 🛠️ Herramientas Necesarias

- **Git**: Para control de versiones
- **Netlify CLI**: Para deploy (`npm install -g netlify-cli`)
- **Node.js**: Para ejecutar herramientas locales
- **Navegador**: Para acceder a GitHub y Netlify

---

## 📝 Notas Importantes

- El sitio usa **Tailwind CSS** (CDN)
- El sitio es **responsive** (mobile-first)
- Los cambios en GitHub se sincronizan automáticamente con Netlify
- Los deploys en Netlify son **instantáneos** (3-5 segundos)
- El favicon se cachea en Google (puede tardar 1-4 semanas en actualizarse)

---

**Última actualización**: 2025-11-22  
**Release actual**: release-con-video-1.0

