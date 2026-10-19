# Página profesional de Erick Alejandro Suárez Cervantes

Este paquete contiene el código completo de la página profesional orientada a automatización industrial.

## Contenido

```text
Pagina_Profesional_Erick_Suarez_Cervantes/
├── index.html
├── styles.css
├── script.js
├── LEEME_PRIMERO.md
└── assets/
    └── erick-alejandro-suarez-cervantes.jpg
```

## Abrir la página

No se requiere instalar programas, servidores ni dependencias.

1. Descomprime el archivo ZIP.
2. Abre la carpeta resultante.
3. Haz doble clic en `index.html`.

La página se abrirá en el navegador predeterminado. Para trabajar con mayor comodidad, abre la carpeta completa en Visual Studio Code.

## Archivo que controla cada parte

- `index.html`: nombre, semblanza, visión, experiencia, proyectos, correo y estructura de la página.
- `styles.css`: colores, tipografías, tamaños, distribución, diseño adaptable y animaciones visuales.
- `script.js`: menú para celular, animaciones al desplazarse, navegación activa y año automático.
- `assets/erick-alejandro-suarez-cervantes.jpg`: fotografía profesional utilizada en la portada.

## Cambiar textos

Abre `index.html` con Visual Studio Code y utiliza `Ctrl + F` para buscar el texto que deseas modificar. Por ejemplo:

- `Erick Alejandro Suárez Cervantes`
- `alexdinamo2004@gmail.com`
- `VISIÓN PROFESIONAL`
- `SEMBLANZA`
- `Remachadora semiautomatizada`

Guarda el archivo con `Ctrl + S` y vuelve a cargar `index.html` en el navegador.

## Cambiar el correo

El correo aparece en dos partes del mismo enlace:

```html
<a href="mailto:alexdinamo2004@gmail.com">
  alexdinamo2004@gmail.com
</a>
```

Si se modifica, se deben cambiar tanto el valor después de `mailto:` como el texto visible.

## Cambiar la fotografía

La forma más sencilla es sustituir el archivo de la carpeta `assets` por otra fotografía conservando exactamente este nombre:

```text
erick-alejandro-suarez-cervantes.jpg
```

Se recomienda una fotografía vertical, con fondo limpio y buena iluminación.

## Cambiar colores

Al principio de `styles.css` se encuentran las variables principales:

```css
:root {
  --navy-950: #04111f;
  --navy-900: #071a2f;
  --teal: #27d3c2;
  --white: #ffffff;
  --surface: #f4f7f9;
}
```

Al modificar estos valores se actualiza la paleta general del sitio.

## Publicación

Estos archivos pueden publicarse como un sitio estático en GitHub Pages, Netlify, Cloudflare Pages u otro servicio similar. Para actualizar la versión que ya se encuentra publicada en ChatGPT Sites, se puede entregar nuevamente el ZIP con los cambios y solicitar la actualización de la misma página.

## Datos actuales

- Nombre: Erick Alejandro Suárez Cervantes
- Orientación profesional: Automatización industrial
- Correo: alexdinamo2004@gmail.com
- Diseño adaptable: computadora, tableta y celular
