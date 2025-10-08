## 🕒 LuxTime — Venta de Relojes de Lujo

### 💎 Descripción del Proyecto

**LuxTime** es una tienda virtual de relojes de lujo diseñada con **HTML y CSS puro**, sin uso de JavaScript.
El objetivo del proyecto es ofrecer una experiencia elegante, moderna y fluida al usuario, manteniendo una estética **sofisticada y minimalista** inspirada en marcas suizas de alta gama.

---

### 🧭 Estructura del Sitio

* **Home (`index.html`)** — Presentación principal con carrusel animado, sección de productos destacados y un diseño responsive.
* **Catálogo (`catalogo.html`)** — Vista general de productos organizados con identificadores únicos (`#producto1`, `#producto2`, etc.).
* **Detalles de producto** — Cada producto cuenta con su propia sección en el mismo HTML, usando IDs y mini-galerías con radio buttons para cambiar imágenes sin JavaScript.
* **Historia (`historia.html`)** — Línea de tiempo interactiva y galería visual que muestran la evolución de LuxTime.
* **Contacto / Footer** — Sección final con enlaces, redes y créditos.

---

### 🎥 Video Corporativo

Archivo: `asset/video/LuxTime.mp4`
**Duración:** 40 segundos
**Estilo:** Realista y elegante
**Colores:** Dorado, negro, gris metálico, azul profundo
**Sinopsis:**

> Desde su fundación artesanal hasta su expansión global, LuxTime celebra la unión entre innovación y tradición. Un legado que sigue marcando el tiempo.

---

### 🧩 Funcionalidades

* 🌐 **Diseño completamente responsive** (desktop, tablet, móvil).
* 🖼️ **Carrusel fluido** con animación CSS pura (`@keyframes moverCarrusel`).
* 🧍 **Galerías interactivas** por producto con selección mediante `<input type="radio">`.
* 🕹️ **Optimización visual** mediante `loading="lazy"` para imágenes.
* 🎞️ **Video institucional** integrado con HTML `<video>`.
* 🧱 **Estructura modular:** cada sección (productos, historia, video, footer) está separada claramente por `section` y `div`.
* 🧠 **Sin uso de JavaScript:** toda la interacción se logra solo con HTML y CSS.

---

### 🗂️ Estructura de Archivos

<pre class="overflow-visible!" data-start="2389" data-end="2674"><div class="contain-inline-size rounded-2xl relative bg-token-sidebar-surface-primary"><div class="sticky top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre!"><span><span>venta-de-relojes/
│
├── index</span><span>.html</span><span>
├── catalogo</span><span>.html</span><span>
├── historia</span><span>.html</span><span>
│
├── css/
│   └── style</span><span>.css</span><span>
│
├── asset/
│   ├── productos/
│   │   ├── hombre/
│   │   ├── mujer/
│   │   └── ...
│   ├── </span><span>video</span><span>/
│   │   └── LuxTime</span><span>.mp4</span><span>
│   └── icons/
│       └── logo</span><span>.ico</span><span>
│
└── README</span><span>.md</span><span>
</span></span></code></div></div></pre>

---

### 📱 Responsive Design

LuxTime utiliza **media queries** cuidadosamente ajustadas para distintas resoluciones:

<pre class="overflow-visible!" data-start="2796" data-end="2909"><div class="contain-inline-size rounded-2xl relative bg-token-sidebar-surface-primary"><div class="sticky top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-css"><span><span>@media</span><span> (</span><span>max-width</span><span>: </span><span>1024px</span><span>) { ... }
</span><span>@media</span><span> (</span><span>max-width</span><span>: </span><span>768px</span><span>) { ... }
</span><span>@media</span><span> (</span><span>max-width</span><span>: </span><span>480px</span><span>) { ... }
</span></span></code></div></div></pre>

Esto permite que los productos, carruseles y textos se adapten perfectamente en móviles y tablets sin pérdida de estética.

---

### 🧭 Inspiración del Diseño

* Tonos principales: **negro, dorado, gris metálico y azul oscuro.**
* Tipografía elegante con detalles de lujo.
* Minimalismo inspirado en marcas como Tissot, Fossil y Diesel.
* Filosofía visual: *“El tiempo es nuestro legado.”*

---

### 👨‍💻 Autor

**Craftube23**
📍 Proyecto académico / portafolio personal.
🔗 [GitHub: craftube23](https://github.com/craftube23)

---

### 📜web

paguina web [LuxTiem - Relojes de lujo](https://vente-relojes.netlify.app/)
