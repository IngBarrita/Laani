# Calaveritas Literarias — CETIS 124

Sitio estático para GitHub Pages con tres secciones (1F, 3F y 3C) y una calaverita principal del profesor Barrita.

## Archivos
- `index.html`: estructura de la página y calaverita principal.
- `styles.css`: diseño adaptable, colores tradicionales, flores y detalles decorativos.
- `script.js`: publicaciones organizadas por grupo.

## Cómo agregar una calaverita
1. Abre `script.js`.
2. En `calaveritas`, localiza el grupo correspondiente: `"1F"`, `"3F"` o `"3C"`.
3. Agrega un objeto con `titulo`, `autor` y `estrofas`.
4. Incluye exactamente seis cadenas dentro de `estrofas`.
5. Guarda el archivo y vuelve a subirlo al repositorio.

Ejemplo:

```js
"1F": [
  {
    titulo: "La Catrina llegó al salón",
    autor: "Nombre del estudiante",
    estrofas: [
      "Primera estrofa...\\nSegundo verso...",
      "Segunda estrofa...\\nSegundo verso...",
      "Tercera estrofa...\\nSegundo verso...",
      "Cuarta estrofa...\\nSegundo verso...",
      "Quinta estrofa...\\nSegundo verso...",
      "Sexta estrofa...\\nSegundo verso..."
    ]
  }
]
```

Si hay varias publicaciones del mismo grupo, sepáralas con una coma entre los objetos.

## Publicar en GitHub Pages
1. Entra en https://github.com e inicia sesión.
2. Pulsa **New repository**.
3. Pon un nombre, por ejemplo `calaveritas-cetis124`, y selecciona **Public**.
4. Crea el repositorio.
5. Pulsa **Add file → Upload files** y sube `index.html`, `styles.css`, `script.js` y `README.md` (puedes descomprimir el ZIP primero).
6. Pulsa **Commit changes**.
7. Abre **Settings → Pages**.
8. En **Build and deployment**, selecciona **Deploy from a branch**.
9. Selecciona la rama **main** y la carpeta **/(root)**; pulsa **Save**.
10. Espera unos minutos. GitHub mostrará la dirección pública de tu página en la sección Pages.

El sitio no requiere base de datos ni servidor. Los cambios se publican al guardar y subir los archivos actualizados al repositorio.
