# TVDIEZ

Sitio estático de TVDIEZ. La página principal está en `index.html` y los recursos locales están en `public/`.

## Publicar con GitHub Pages

1. En GitHub, crea un repositorio nuevo. Si quieres que los archivos del proyecto no sean visibles para otras personas, déjalo **privado**. GitHub Pages puede requerir un plan compatible para publicar desde repositorios privados; comprueba las opciones que GitHub te muestre.
2. Sube `index.html`, `public/`, `.gitignore` y este `README.md` a la raíz del repositorio. No subas `.taste/`.
3. En el repositorio, abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**, selecciona `main` y la carpeta `/(root)`, y guarda.
5. Espera a que termine la publicación. GitHub mostrará allí la dirección del sitio.

No se necesita instalar dependencias ni ejecutar un comando de compilación. La página carga Three.js y Google Fonts desde servicios externos, así que esas partes necesitan conexión a Internet. Las imágenes y los archivos de Figtree están guardados en `public/`.

## Editar y publicar cambios

Puedes editar `index.html` y los archivos de `public/` directamente desde GitHub con el botón del lápiz, o descargar/clonar el repositorio, editar los archivos y subir los cambios. Cada cambio guardado en la rama `main` inicia una nueva publicación de Pages.

Antes de hacer cambios grandes, descarga una copia de los archivos o crea un commit para poder volver atrás.
