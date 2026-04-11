# FlyTurismo — Armador de Flyers para Turismo

Web app estática, lista para deployar en **GitHub Pages**, para crear flyers de paquetes turísticos desde navegador y sin backend.

## Qué quedó resuelto

- **Responsive real**: usable desde desktop, tablet y celular.
- **Vista previa del flyer desde el teléfono** con ajuste automático al ancho disponible.
- **Modos de simulación visual**: Auto, Celular, Tablet y Desktop.
- **Modo de escala**: Ajustar o 100%.
- **Exportación** en PNG y JPEG.
- **Sin servidor**, sin base de datos y sin instalación.

## Deploy en GitHub Pages

1. Crear un repositorio nuevo en GitHub.
2. Subir estos archivos a la raíz del repo.
3. Ir a **Settings → Pages**.
4. Elegir **Deploy from branch**.
5. Seleccionar rama **main** y carpeta **/(root)**.
6. Guardar.

## Estructura

```bash
/
├── index.html
├── app.html
└── README.md
```

## Tecnologías

- HTML5
- CSS3
- JavaScript vanilla
- html2canvas vía CDN

## Observación operativa

La vista previa puede escalarse visualmente para trabajar mejor en pantallas chicas, pero la exportación mantiene el tamaño real del formato elegido.
