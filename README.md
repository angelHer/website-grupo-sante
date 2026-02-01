# Grupo Santé - Sitio Web Oficial

Sitio web oficial de **Grupo Santé Radiodiagnóstico Médico**, centro especializado en estudios de diagnóstico por imagen en Pachuca, Hidalgo.

## 🏥 Acerca del Proyecto

Este sitio web fue desarrollado para Grupo Santé, un centro médico especializado en:
- Ultrasonidos
- Rayos X (Radiografías)
- Electrocardiogramas
- Densitometrías
- Análisis Clínicos

## 🚀 Tecnologías

- **[Astro](https://astro.build)** - Framework web moderno y rápido
- **Vanilla CSS** - Estilos personalizados sin frameworks
- **JavaScript** - Interactividad y animaciones
- **SEO Optimizado** - Meta tags y structured data para búsqueda local

## 📋 Características

- ✅ Diseño responsivo (móvil, tablet, desktop)
- ✅ Optimizado para SEO local
- ✅ Integración con WhatsApp para agendado de citas
- ✅ Accesibilidad (WCAG)
- ✅ Animaciones fluidas
- ✅ Mapa de ubicación integrado
- ✅ Testimonios de clientes
- ✅ Información de servicios detallada

## 🛠️ Instalación y Desarrollo

### Requisitos Previos

- Node.js 18+ 
- npm o pnpm

### Instalación

```bash
# Clonar el repositorio
git clone https://github.com/TU-USUARIO/grupo-sante-site.git

# Navegar al directorio
cd grupo-sante-site

# Instalar dependencias
npm install
```

### Comandos Disponibles

```bash
# Iniciar servidor de desarrollo
npm run dev

# Compilar para producción
npm run build

# Vista previa de la compilación
npm run preview
```

## 📁 Estructura del Proyecto

```
/
├── public/              # Archivos estáticos
│   ├── images/         # Imágenes y logos
│   ├── favicon.png     # Favicon del sitio
│   └── robots.txt      # SEO
├── src/
│   ├── components/     # Componentes Astro
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── Services.astro
│   │   ├── About.astro
│   │   ├── Process.astro
│   │   ├── Testimonials.astro
│   │   ├── Location.astro
│   │   ├── Footer.astro
│   │   └── WhatsAppButton.astro
│   ├── layouts/        # Layouts base
│   │   └── Layout.astro
│   ├── pages/          # Páginas del sitio
│   │   └── index.astro
│   └── styles/         # Estilos globales
│       ├── global.css
│       └── animations.css
└── package.json
```

## 🌐 Deploy

Este proyecto está configurado para deploy automático en Vercel/Netlify.

### Deploy en Vercel

1. Conecta tu repositorio de GitHub a Vercel
2. Vercel detectará automáticamente la configuración de Astro
3. Deploy automático en cada push a `main`

### Deploy en Netlify

Build settings:
- **Build command:** `npm run build`
- **Publish directory:** `dist`

## 📞 Información de Contacto

**Grupo Santé Radiodiagnóstico Médico**
- 📍 Blvd. Valle de San Javier 301, Plaza de las Américas, Pachuca, Hidalgo
- 📱 WhatsApp: +52 771 190 6926
- ☎️ Teléfono: 771 107 2370
- ✉️ Email: rrodriguezsante@gmail.com

## 📄 Licencia

© 2026 Grupo Santé Radiodiagnóstico Médico. Todos los derechos reservados.

---

Desarrollado con ❤️ en Pachuca, Hidalgo
