# Crear una página web estática con HTML y CSS

En este tutorial aprenderás a crear una página web estática utilizando **HTML** y **CSS**. Este es un excelente punto de partida para los que desean aprender cómo construir páginas web simples pero efectivas. 

## ¿Qué aprenderás?

- Estructura básica de una página web con HTML.
- Cómo usar etiquetas HTML para estructurar contenido.
- Introducción al CSS para dar estilo a tu página web.
- Cómo enlazar tu archivo CSS a tu archivo HTML.

---

## Paso 1: Estructura básica de HTML

Primero, vamos a crear la estructura básica de una página HTML. Un archivo HTML comienza con las siguientes etiquetas básicas:

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Primera Página</title>
</head>
<body>
    <h1>Bienvenidos a mi página web</h1>
    <p>Este es un párrafo de ejemplo.</p>
</body>
</html>
```

---

## Paso 2: Agregar estilos con CSS

Ahora que tenemos la estructura HTML básica, vamos a agregar un archivo CSS para darle estilo. Crea un archivo llamado `styles.css` y vincúlalo a tu archivo HTML de la siguiente manera:

```html
<head>
    <link rel="stylesheet" href="styles.css">
</head>
```

En tu archivo `styles.css`, agrega algo de estilo básico como:

```css
body {
    background-color: #f0f0f0;
    font-family: Arial, sans-serif;
}

h1 {
    color: #4CAF50;
}

p {
    font-size: 16px;
}
```

---

## Paso 3: Ver tu página

Una vez que hayas creado tu archivo HTML y tu archivo CSS, simplemente **abre el archivo HTML en tu navegador** para ver el resultado.

---

## ¡Listo!

Ya has creado una página web estática con HTML y CSS. Ahora puedes personalizarla y agregar más elementos como imágenes, listas, tablas, enlaces, y mucho más.

---

## Recursos adicionales

- [Documentación oficial de HTML](https://developer.mozilla.org/es/docs/Web/HTML)
- [Documentación oficial de CSS](https://developer.mozilla.org/es/docs/Web/CSS)
- [Guía de CSS para principiantes (MDN)](https://developer.mozilla.org/es/docs/Learn/CSS)
