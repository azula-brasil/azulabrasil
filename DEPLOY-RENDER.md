# Desplegar en Render

Esta pagina es una web estatica. En Render debes crear un **Static Site**.

## Opcion recomendada

1. Sube esta carpeta a GitHub.
2. Entra en Render: https://render.com
3. Pulsa **New +**.
4. Elige **Static Site**.
5. Conecta tu repositorio de GitHub.
6. Usa estos valores:

   - **Name:** `azula-brasil-portfolio`
   - **Branch:** `main`
   - **Build Command:** dejar vacio
   - **Publish Directory:** `.`

7. Pulsa **Create Static Site**.

Render te dara una URL parecida a:

`https://azula-brasil-portfolio.onrender.com`

## Importante

No subas solo `index.html`. Tienes que subir tambien las imagenes y la carpeta `digital-art`, porque el HTML las usa desde el proyecto.
