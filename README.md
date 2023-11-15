

html
Copy code
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio de Desarrollador Web</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>Tu Nombre</h1>
        <p>Desarrollador Web</p>
    </header>

    <section id="sobre-mi">
        <h2>Sobre Mí</h2>
        <p>Breve descripción sobre ti y tu experiencia como desarrollador web.</p>
    </section>

    <section id="habilidades">
        <h2>Habilidades</h2>
        <ul>
            <li>HTML5</li>
            <li>CSS3</li>
            <li>JavaScript</li>
            <!-- Agrega más habilidades según sea necesario -->
        </ul>
    </section>

    <section id="proyectos">
        <h2>Proyectos Destacados</h2>
        <!-- Lista de proyectos con enlaces y descripciones -->
        <div class="proyecto">
            <h3>Nombre del Proyecto 1</h3>
            <p>Descripción breve del proyecto.</p>
            <a href="#">Enlace al Proyecto</a>
        </div>
        <div class="proyecto">
            <h3>Nombre del Proyecto 2</h3>
            <p>Descripción breve del proyecto.</p>
            <a href="#">Enlace al Proyecto</a>
        </div>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>Información de contacto: correo electrónico, enlaces a redes sociales, etc.</p>
    </section>

    <footer>
        <p>&copy; 2023 Tu Nombre. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
Recuerda personalizar la información según tus datos y proyectos. Además, puedes mejorar el diseño utilizando CSS y añadir interactividad con JavaScript si lo deseas.




User
You
Crea los estilos de CSS de ese HTML. Usa la font que se llama IBM y una paleta de colores verdes

3 / 3


ChatGPT
ChatGPT
Aquí tienes un ejemplo de estilos CSS utilizando la fuente IBM y una paleta de colores verdes. Puedes ajustar los estilos según tus preferencias:

css
Copy code
body {
    font-family: 'IBM', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
    color: #333;
}

header {
    background-color: #4CAF50;
    color: #fff;
    text-align: center;
    padding: 1em 0;
}

header h1 {
    margin: 0;
}

section {
    padding: 20px;
}

h2 {
    color: #4CAF50;
}

ul {
    list-style: none;
    padding: 0;
}

li {
    margin-bottom: 5px;
}

.proyecto {
    border: 1px solid #ddd;
    padding: 10px;
    margin-bottom: 15px;
}

footer {
    background-color: #4CAF50;
    color: #fff;
    text-align: center;
    padding: 1em 0;
    position: absolute;
    bottom: 0;
    width: 100%;
}
