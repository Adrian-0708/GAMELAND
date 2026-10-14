# 🎮 GAMELAND

Página web de una tienda de videojuegos ficticia, con un diseño oscuro de estilo "gaming", animaciones en CSS y un catálogo de ofertas destacadas. Proyecto final de Lenguajes de Marcas (LM).

## ✨ Características

- **Cabecera fija** con logo, buscador y navegación (Tienda, carrito y Login). Se mantiene visible al hacer scroll y tiene efecto de desenfoque.
- **Carrusel de fondo** en la sección principal: 5 imágenes que se van alternando con un fundido, hecho solo con animaciones CSS (sin JavaScript).
- **Categorías populares** con efecto acordeón: PC, PlayStation, Xbox y Nintendo. Al pasar el ratón, la categoría se expande y muestra su nombre.
- **Ofertas destacadas** en una cuadrícula adaptable con 8 juegos, cada uno con:
  - portada, etiqueta de plataforma (PC, PS4, PS5, XBOX, SWITCH) y etiqueta de descuento,
  - precio actual y precio anterior tachado,
  - ventanita flotante (tooltip) al pasar el ratón, con clasificación **PEGI**, descripción y precio.
- **Diseño responsive**: en pantallas de hasta 768 px la cabecera y las categorías se apilan en vertical.
- Animaciones de entrada, brillos de neón y transiciones suaves.

## 🛠️ Tecnologías

- **HTML5**: estructura semántica (`header`, `nav`, `main`, `section`, `article`, `footer`).
- **CSS3**: variables CSS, Flexbox, Grid, `@keyframes`, transiciones, `backdrop-filter` y media queries.

## 📁 Estructura del proyecto

```
Trabajo-final/
├── index.html                              # Estructura de la página
├── style.css                               # Estilos y animaciones
├── Captura de pantalla 2026-03-18 141158.png   # Imagen del carrusel
├── Captura de pantalla 2026-03-18 141234.png   # Imagen del carrusel
├── Captura de pantalla 2026-03-18 141257.png   # Imagen del carrusel
├── Captura de pantalla 2026-03-18 141321.png   # Imagen del carrusel
└── README.md
```

## 🚀 Cómo ejecutarlo

No necesita instalación ni dependencias.

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Adrian-0708/Trabajo-final.git
   ```
2. Entra en la carpeta:
   ```bash
   cd Trabajo-final
   ```
3. Abre `index.html` en tu navegador (doble clic, o con la extensión *Live Server* de VS Code).

> **Nota:** las portadas de los juegos y la quinta imagen del carrusel se cargan desde internet (Amazon y Unsplash), así que hace falta conexión para verlas.

## 📌 Estado del proyecto

Es una maqueta de interfaz: el buscador, el carrito, el login y los enlaces todavía no tienen funcionalidad. Posibles mejoras futuras:

- Añadir JavaScript para el buscador y el contador del carrito.
- Crear páginas para cada categoría y para cada juego.
- Guardar las portadas en el propio repositorio para no depender de enlaces externos.

## 👤 Autor

**Adrian-0708** · [github.com/Adrian-0708](https://github.com/Adrian-0708)

---

© 2026 GAMELAND. Proyecto final LM.
