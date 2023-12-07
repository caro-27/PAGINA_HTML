/* Reset de estilos para eliminar márgenes y rellenos predeterminados del navegador */
body, h1, h2, p, ul, li {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Estilo para el cuerpo de la página */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f8f8f8;
    color: #333;
    line-height: 1.6;
}

/* Estilo para el encabezado */
header {
    background-color: #1F9FB6;
    color: #fff;
    padding: 1em;
    text-align: center;
}

/* Estilo para el logo */
.logo {
    display: block;
    margin: 0 auto;
    max-width: 100%;
    height: auto;
}

/* Estilo para la navegación */
nav {
    margin-top: 10px;
}

nav ul {
    list-style: none;
    text-align: center;
}

nav ul li {
    display: inline;
    margin-right: 10px;
}

nav a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
    padding: 8px 16px;
    border-radius: 4px;
    background-color: #0E707E;
}

nav a:hover {
    background-color: #1F9FB6;
}

/* Estilo para las secciones */
main {
    padding: 20px;
}

/* Estilo para la sección de inicio */
.inicio {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin-bottom: 20px;
}

.inicio h2 {
    color: #1F9FB6;
}

/* Estilo para el pie de página */
footer {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
}
