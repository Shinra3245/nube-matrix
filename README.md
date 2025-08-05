# ☁️ Neon Cloud with Matrix Rain Animation

Una animación visual ligera, responsiva y personalizable desarrollada con HTML, CSS y JavaScript puro. Este proyecto presenta una nube con estilo neón que deja caer una lluvia de símbolos aleatorios al estilo *Matrix*, ideal para portafolios, fondos animados o presentaciones creativas.

## 🚀 Vista previa

🔗 [Ver animación en vivo](https://omarbolanos.netlify.app/) 

![Preview](preview.PNG) <!-- Puedes subir una captura y renombrarla así -->

---

## 🧩 Tecnologías utilizadas

- HTML5
- CSS3 (con animaciones y variables CSS)
- JavaScript vanilla

---

## 🎨 Características

- 🌈 **Efecto Neón animado** mediante `drop-shadow` y `hue-rotate`.
- 🧠 **Símbolos Matrix aleatorios** generados dinámicamente.
- 📱 **Responsivo**: ajusta la cantidad de gotas para móviles automáticamente.
- ⚡ **Alto rendimiento**: sin librerías externas ni frameworks pesados.
- 🛠️ **Código modular y fácil de personalizar** (colores, símbolos, velocidad, etc.).

---

## 📂 Estructura del proyecto
├── index.html # Estructura principal
├── nube.css # Estilos de nube y lluvia
├── rain.js # Lógica de animación Matrix

Edita la variable CSS en `nube.css`:

```css
:root {
  --clr: #00fff0; /* Cambia este valor por otro color neón */
}
```

💧 Cambiar los caracteres de la lluvia
Edita la función randomText() en rain.js:
``` rain.js
function randomText() {
  const text = "01ｱｳｴｵｶｷｸｹｺ"; // Cambia o agrega caracteres tipo Matrix
  return text[Math.floor(Math.random() * text.length)];
}
```
Creado con 💡 y 💻 por [Omar Bolaños / Shinra3245]

