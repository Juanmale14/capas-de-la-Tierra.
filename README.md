
# 🌍 Capas de la Tierra — Interactivo (ES/EN)

Explorador de las capas de la Tierra con **diagrama en corte transversal**, **flechas con nombres al lado**, **botones por capa**, **tooltips**, **zoom**, **locución** (Web Speech API), **modo Aula/Experto**, y **animaciones** de **convección** y **geodinamo**.

## 🚀 Demo local
Abre `index.html` directamente en tu navegador.

## 🧭 Controles
- **Botones por capa** o clic en **anillos/flechas** para ver la ficha.
- **Flechas/etiquetas**: alterna visibilidad.
- **Geodinamo** y **Convección**: activar/desactivar animaciones.
- **Zoom**: deslizador (80–160%).
- **Locución**: lectura de la ficha (según idioma).
- **Modo experto**: muestra más datos (porcentaje, densidad, mineralogía).
- **Idioma**: ES | EN (UI, fichas, tooltips y nombres junto a flechas).

## ♿ Accesibilidad
- Navegable con teclado: **Tab** para enfocar, **Enter** para abrir fichas.
- Rótulos junto a flechas con **alto contraste** (halo de trazo).
- Narración (si el navegador soporta Web Speech API).

## 🛠️ Cómo publicar en GitHub Pages
1. Crea un repo, por ejemplo `capas-tierra-interactivo`.
2. Sube los archivos: `index.html`, `README.md`, `LICENSE` (opcional), `.nojekyll`.
3. Ve a **Settings → Pages**:
   - **Build and deployment** → *Deploy from a branch*
   - Branch: **main** — Folder: **/** (root)
   - Guarda. GitHub generará una URL como `https://<tu-usuario>.github.io/capas-tierra-interactivo/`
4. (Opcional) Dominio propio: añade tu dominio en **Settings → Pages** y crea `CNAME` con ese dominio.

> Alternativa: pon los archivos en `/docs` y selecciona *docs* como carpeta en Pages.

## 🧩 Navegadores
- Chrome/Edge/Opera: OK
- Firefox: OK (Web Speech API puede variar)
- Safari/iOS: OK (algunos permisos para voz)

## 📚 Créditos y fuentes (para docencia)
- **USGS** — *Inside the Earth* (capas, espesores, núcleo externo líquido / interno sólido)  
  https://pubs.usgs.gov/gip/dynamic/inside.html
- **USGS** — *How does the Earth's core generate a magnetic field?* (geodinamo)  
  https://www.usgs.gov/faqs/how-does-earths-core-generate-a-magnetic-field
- **Encyclopaedia Britannica** — *The interior* (composición, temperaturas estimadas, Moho)  
  https://www.britannica.com/place/Earth/The-interior
- **NASA** — *Cut‑away Diagram of Earth’s Interior* (divulgación núcleo/geodinamo)  
  https://www.nasa.gov/image-article/cut-away-diagram-of-earths-interior/

## 📝 Licencia
MIT — ver `LICENSE`.
