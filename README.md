# 🎵 GalleryMusic

Sitio web estático y minimalista donde recopilo información, contexto histórico y muestras audiovisuales sobre los géneros musicales que más suelo escuchar.

🌐 **Demo en vivo:** [gallerymusic.netlify.app](https://netlify.app)

---

## ✨ Características

* **Diseño minimalista y responsivo:** Adaptado a dispositivos móviles, tablets y pantallas de escritorio mediante Flexbox y unidades relativas (`rem` y `clamp()`).
* **Microinteracciones suaves:** Tarjetas con elevación al pasar el cursor (`hover`) y animaciones de subrayado progresivo en enlaces.
* **Galería por géneros:** Páginas individuales con reseña histórica y reproductor de video integrado para cada estilo musical:
  * **Cumbia Rebajada**
  * **Gabber**
  * **Hip Hop**
  * **Hardcore Punk**

---

## 🛠️ Tecnologías utilizadas

* **HTML5** semántico.
* **CSS3** puro (Custom Properties, Flexbox, `aspect-ratio`, media queries).
* **Google Fonts** (`Azeret Mono`, `Lexend` y `Montserrat`).

---

## 📂 Estructura del proyecto

```text
GalleryMusic/
├── assets/             # Imágenes de portada de cada género e ícono del sitio
│   ├── cumbia.png
│   ├── gabber.png
│   ├── hiphop.png
│   ├── iconLogo.png
│   └── punk1.png
├── html/               # Vistas individuales por género musical
│   ├── cumbia.html
│   ├── gabber.html
│   ├── hiphop.html
│   └── punk.html
├── styles/             # Hojas de estilo
│   ├── reset.css       # Normalización de estilos y variables globales
│   ├── style.css       # Estilos de la página principal (galería)
│   └── styleOther.css  # Estilos de las vistas de cada género
├── index.html          # Página de inicio
├── LICENSE             # Licencia GNU GPL v3.0
└── README.md           # Documentación del proyecto
```

---

## 🚀 Cómo ejecutarlo en local

No requiere dependencias ni herramientas de compilación. Solo sigue estos pasos:

1. Clona este repositorio:
   ```bash
   git clone https://github.com
   ```
2. Entra en la carpeta del proyecto:
   ```bash
   cd GalleryMusic
   ```
3. Abre el archivo `index.html` en tu navegador favorito (o usa la extensión **Live Server** en Visual Studio Code).

---

Desarrollado por [@malsebasmal](https://github.com)
