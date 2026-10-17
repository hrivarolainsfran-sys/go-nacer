# Nacer del Espíritu · Go!

Web y app de la dinámica «Glow up · El perfil de Nicodemo» (Lección #3, Juan 3).

Es una sola carpeta que funciona como **página web** y como **app instalable** en el celular (PWA). Después de abrirla una vez con internet, también funciona sin conexión.

## Qué hay en la carpeta

| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | La app completa |
| `manifest.webmanifest` | Nombre, colores e ícono de la app instalada |
| `sw.js` | Guarda la app para usarla sin internet |
| `icons/` | Ícono de Go! para el celular y la pestaña |

## 1. Publicarla en internet (gratis)

La forma más fácil es **Netlify Drop**:

1. Entra a https://app.netlify.com/drop (puedes crear una cuenta gratis con tu correo).
2. Arrastra la carpeta `go-nacer-del-espiritu` (o el archivo `.zip`) a la página.
3. En unos segundos te da un enlace, por ejemplo `https://go-nacer.netlify.app`. En la configuración del sitio puedes cambiar el nombre.

Otras opciones: GitHub Pages, Vercel o Cloudflare Pages. Solo hay que subir estos archivos tal cual.

Importante: para que se pueda instalar como app, el enlace tiene que empezar con `https://` (Netlify y las demás ya lo hacen).

## 2. Instalarla como app en el celular

**iPhone (Safari):** abre el enlace → botón Compartir → «Agregar a pantalla de inicio».

**Android (Chrome):** abre el enlace → menú ⋮ → «Instalar app» (o «Agregar a la pantalla principal»).

Queda con el ícono de Go! y se abre a pantalla completa, sin la barra del navegador.

## 3. Hacer cambios

- Los textos (opciones del glow up, frases de Nicodemo y frases del apagón) están al principio del código, dentro de `index.html`, en `CATEGORIAS`, `NICO` y `LINEAS`.
- Después de cambiar algo, abre `sw.js` y sube el número de versión (`go-nacer-v1` → `go-nacer-v2`) para que los celulares que ya la instalaron reciban el cambio.
- Vuelve a subir la carpeta a Netlify (en tu sitio: Deploys → arrastrar la carpeta de nuevo).

## Texto bíblico

Santa Biblia, Nueva Traducción Viviente, © Tyndale House Foundation, 2010.
