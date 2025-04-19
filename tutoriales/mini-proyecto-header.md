# Mini proyecto página web: Agregar un encabezado

En este tutorial aprenderás cómo agregar un encabezado básico a una página web estática utilizando **HTML** y **CSS**. Un encabezado es una de las partes fundamentales de cualquier página web, ya que generalmente contiene el logo, el título de la página y, en algunos casos, el menú de navegación.

## ¿Qué aprenderás?

- Crear un encabezado con HTML.
- Estilizar un encabezado usando CSS.
- Implementar un menú de navegación básico en el encabezado.

---

## Paso 1: Estructura básica de HTML

Primero, vamos a crear la estructura básica de HTML para nuestro encabezado. Abre tu editor de código y crea un archivo `index.html`.

Dentro del archivo, agrega lo siguiente:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mini Proyecto - Agregar un Encabezado</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <!-- Encabezado -->
  <header>
    <div class="logo">
      <h1>Mi Sitio Web</h1>
    </div>
    <nav>
      <ul>
        <li><a href="#">Inicio</a></li>
        <li><a href="#">Sobre mí</a></li>
        <li><a href="#">Contacto</a></li>
      </ul>
    </nav>
  </header>

</body>
</html>
```

---

## Paso 2: Estilizando con CSS

Ahora, vamos a darle estilo al encabezado para que se vea más atractivo. Crea un archivo `styles.css` y agrega lo siguiente:

```css
/* Estilos básicos */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
}

header {
  background-color: #4CAF50;
  color: white;
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header .logo h1 {
  margin: 0;
  font-size: 24px;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  display: flex;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  text-decoration: none;
  color: white;
  font-weight: bold;
}

nav ul li a:hover {
  text-decoration: underline;
}
```

---

## Paso 3: Resultado final

Con estos cambios, tu página tendrá un encabezado con el siguiente aspecto:

- Un título a la izquierda con el nombre de tu sitio web.
- Un menú de navegación a la derecha con enlaces que cambian de estilo cuando se pasa el cursor sobre ellos.

Este es un ejemplo muy básico, pero puedes personalizarlo y ampliarlo según tus necesidades. Puedes añadir más estilos, cambiar los colores y experimentar con diferentes estructuras.

---

## ¡Listo!

Ahora has aprendido a crear y estilizar un encabezado básico en HTML y CSS. Este es un paso importante para darle estructura a tu página web.

---

## Recursos adicionales

- [MDN Web Docs - Header](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header)
- [CSS Flexbox - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout/Basic_concepts_of_flexbox)
- [Guía de CSS Básico](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/CSS_basics)

¡Felicidades por completar este mini proyecto! 🎉
