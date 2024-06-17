<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Blog Personal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
        }
        nav a {
            color: #fff;
            padding: 1rem;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background: #555;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            overflow: hidden;
            padding: 0 2rem;
        }
        #about, #blog, #projects, #contact {
            padding: 2rem 0;
        }
        .post, .project {
            background: #fff;
            margin: 1rem 0;
            padding: 1rem;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            margin-top: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mi Blog Personal</h1>
        <p>Bienvenidos a mi espacio personal en la web</p>
    </header>
    <nav>
        <a href="#about">Sobre Mí</a>
        <a href="#blog">Blog</a>
        <a href="#projects">Proyectos</a>
        <a href="#contact">Contacto</a>
    </nav>
    <div class="container">
        <section id="about">
            <h2>Sobre Mí</h2>
            <p>¡Hola! Soy [Tu Nombre], un apasionado por [tu profesión/intereses]. En este blog, compartiré mis pensamientos, proyectos y todo lo que me apasiona. ¡Gracias por visitar!</p>
        </section>
        <section id="blog">
            <h2>Blog</h2>
            <div class="post">
                <h3>Título del Post</h3>
                <p>Contenido del post. Aquí puedes escribir sobre cualquier tema que te interese.</p>
            </div>
            <!-- Puedes duplicar la estructura anterior para más posts -->
        </section>
        <section id="projects">
            <h2>Proyectos</h2>
            <div class="project">
                <h3>Nombre del Proyecto</h3>
                <p>Descripción breve del proyecto. Puedes incluir enlaces, imágenes, y cualquier detalle relevante.</p>
            </div>
            <!-- Puedes duplicar la estructura anterior para más proyectos -->
        </section>
        <section id="contact">
            <h2>Contacto</h2>
            <form action="mailto:tu-email@example.com" method="post" enctype="text/plain">
                <label for="name">Nombre:</label>
                <input type="text" id="name" name="name"><br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email"><br>
                <label for="message">Mensaje:</label><br>
                <textarea id="message" name="message" rows="4" cols="50"></textarea><br>
                <input type="submit" value="Enviar">
            </form>
        </section>
    </div>
    <footer>
        <p>© 2024 Nacional-Socialismo Todos los derechos reservados.</p>
    </footer>
</body>
</html>
