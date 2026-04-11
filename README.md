# FlyTurismo — Armador de Flyers para Turismo

Una web app 100% cliente (sin backend) para crear flyers profesionales de paquetes turísticos en minutos. Lista para deployar en **GitHub Pages** sin ninguna configuración extra.

## 🚀 Deploy en GitHub Pages

1. Creá un repositorio en GitHub (público)
2. Subí todos los archivos de esta carpeta a la rama `main`
3. En Settings → Pages → Source: **Deploy from branch** → `main` → `/ (root)`
4. En unos minutos tu app estará en `https://tu-usuario.github.io/nombre-repo/`

## 📁 Estructura

```
/
├── index.html      ← Landing page
├── app.html        ← Armador de flyers (la app)
└── README.md
```

## ✨ Funcionalidades

- **6 plantillas** de turismo (océano, atardecer, aventura, ciudad, lujo, playa)
- **6 formatos** de exportación: IG Feed, IG Story, FB Post, LinkedIn, WhatsApp, Horizontal
- **Identidad de marca**: logo propio, colores, nombre de agencia, contacto
- **Marca guardada** en localStorage (persiste entre sesiones)
- **Exportación PNG/JPEG** en alta resolución (hasta 3×)
- **Sin registro**, sin backend, sin dependencias externas (excepto html2canvas via CDN)

## 🛠️ Tecnologías

- HTML5 / CSS3 / Vanilla JS
- [html2canvas](https://html2canvas.hertzen.com/) para exportación
- Google Fonts (Playfair Display, DM Sans, Montserrat)

## 📱 Formatos soportados

| Canal | Dimensiones |
|-------|------------|
| Instagram Feed | 1080×1080 px |
| Instagram Story | 1080×1920 px |
| Facebook Post | 1200×630 px |
| LinkedIn Post | 1200×627 px |
| WhatsApp Estado | 1080×1920 px |
| Horizontal/Banner | 1920×720 px |

## 🔒 Privacidad

Todos los datos (logo, colores, textos) se guardan **únicamente en el dispositivo del usuario** via localStorage. No hay servidor, no hay base de datos, no hay tracking.

## 📄 Licencia

MIT — Libre para uso personal y comercial.
