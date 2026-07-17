# Contenido Multimedia Responsive

Página informativa construida con **HTML5** y **CSS3** que documenta, con ejemplos funcionales, las técnicas más usadas para integrar **imágenes responsivas, video y audio** en la web, además de un compendio de buenas prácticas (formatos, pesos y resoluciones recomendadas) para optimizar el rendimiento de contenido multimedia.

🔗 **Demo en vivo:** [alexander404-hz.github.io/Informativo-Multimedia](https://alexander404-hz.github.io/Informativo-Multimedia/)

[![Vista previa](assets/img/readme.png)](https://alexander404-hz.github.io/Informativo-Multimedia/)

## ✨ Características

- **Imágenes responsivas con `srcset` y `sizes`**: el navegador elige automáticamente la versión más adecuada de la imagen (400px, 800px o 1200px) según el tamaño de pantalla, optimizando el consumo de datos.
- **Art direction con `<picture>`**: distintas imágenes (no solo distintas resoluciones) según el dispositivo — encuadre vertical en móvil, horizontal en escritorio — usando `<source media="...">`.
- **Video HTML5** con múltiples formatos (`webm` y `mp4`), imagen de vista previa (`poster`), carga diferida (`preload="metadata"`) y soporte de subtítulos mediante `<track>`.
- **Audio HTML5** con múltiples formatos (`ogg` y `mp3`) y carga bajo demanda (`preload="none"`).
- **Video embebido de YouTube** vía `<iframe>`, explicando las ventajas del streaming externo frente al alojamiento propio.
- **Buenas prácticas documentadas en tablas comparativas**:
  - Formatos de imagen (JPG, WEBP, PNG, SVG)
  - Formatos de video (MP4, WebM, Ogg)
  - Formatos de audio (MP3, OGG, WAV)
  - Resoluciones recomendadas por tipo de dispositivo
  - Pesos ideales y límites máximos para imágenes, video y audio según su uso
- **Optimización de rendimiento**: uso de `loading="lazy"`, `decoding="async"` y estrategias de `preload` orientadas a mejorar métricas como el _Largest Contentful Paint_ (LCP).
- **Metadatos SEO y redes sociales**: Open Graph y Twitter Cards configurados para una correcta previsualización al compartir el enlace.
- Navegación interna con enlace de retorno al inicio (`#top`) y al portafolio del autor.

## 📁 Estructura del proyecto

```
Informativo-Multimedia/
├── assets/
│   ├── css/
│   │   └── styles.css              # Estilos del sitio
│   ├── icons/                      # Favicon en formato SVG
│   ├── img/                        # Imágenes de ejemplo (responsivas, picture, poster, preview)
│   ├── video/                      # Videos de demostración (webm, mp4)
│   └── audio/                      # Audios de demostración (ogg, mp3)
├── favicon.ico                     # Favicon principal
├── index.html                      # Página principal con todos los ejemplos
└── site.webmanifest                # Manifiesto web (PWA / íconos)
```

## 🧩 Secciones de la página

| Sección                                  | Contenido                                                                        |
| ---------------------------------------- | -------------------------------------------------------------------------------- |
| **Galería Multimedia**                   | Introducción al tema                                                             |
| **Imágenes responsivas**                 | Ejemplo con `srcset` / `sizes`                                                   |
| **Adaptación de imágenes con `picture`** | Ejemplo de art direction según dispositivo                                       |
| **Integración de video**                 | Elemento `<video>` con múltiples formatos, poster y subtítulos                   |
| **Integración de audio**                 | Elemento `<audio>` con múltiples formatos                                        |
| **Video embebido desde YouTube**         | Integración mediante `<iframe>`                                                  |
| **Buenas prácticas**                     | Tablas de formatos, resoluciones y pesos recomendados para imagen, video y audio |
| **Conclusiones**                         | Resumen sobre optimización multimedia y su impacto en SEO/rendimiento            |

## 🚀 Uso

Este proyecto no requiere instalación ni dependencias. Solo necesitas un navegador web.

1. Clona el repositorio:
   ```bash
   git clone https://github.com/alexander404-hz/Informativo-Multimedia.git
   ```
2. Entra a la carpeta del proyecto:
   ```bash
   cd Informativo-Multimedia
   ```
3. Abre `index.html` directamente en tu navegador, o sirve el proyecto con un servidor local (por ejemplo, la extensión _Live Server_ de VS Code) para asegurar la correcta carga de recursos multimedia.

## 🛠️ Tecnologías utilizadas

- HTML5 (elementos `img`, `picture`, `video`, `audio`, `iframe`, `track`)
- CSS3

## 👤 Autor

**Alexander Hernández**
Portafolio: [alexander404-hz.github.io/Portafolio](https://alexander404-hz.github.io/Portafolio/)

## 📄 Licencia

© 2026 Alexander Hernández. Todos los derechos reservados.
