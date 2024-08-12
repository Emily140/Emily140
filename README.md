<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Personal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #0056b3;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #003d7a;
            padding: 10px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
        }
        section {
            padding: 20px;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #003d7a;
            color: #fff;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        h1, h2 {
            color: #0056b3;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mi Página Personal</h1>
    </header>
    <nav>
        <a href="#about">Sobre Mí</a>
        <a href="#projects">Proyectos</a>
        <a href="#contact">Contacto</a>
    </nav>
    <section id="about">
        <div class="container">
            <h2>Sobre Mí</h2>
            <p>¡Hola! Soy [Tu Nombre], y este es un espacio donde muestro mis trabajos y proyectos por diversión. Me apasiona [tu pasión o área de interés].</p>
        </div>
    </section>
    <section id="projects">
        <div class="container">
            <h2>Mis Proyectos</h2>
            <p>Aquí puedes ver algunos de los proyectos en los que he trabajado:</p>
            <ul>
                <li><strong>Proyecto 1:</strong> Descripción breve del proyecto.</li>
                <li><strong>Proyecto 2:</strong> Descripción breve del proyecto.</li>
                <li><strong>Proyecto 3:</strong> Descripción breve del proyecto.</li>
            </ul>
        </div>
    </section>
    <section id="contact">
        <div class="container">
            <h2>Contacto</h2>
            <p>Puedes contactarme a través de los siguientes medios:</p>
            <p>Email: <a href="mailto:tuemail@ejemplo.com">tuemail@ejemplo.com</a></p>
            <p>Redes Sociales: <a href="https://www.linkedin.com/in/tu-perfil" target="_blank">LinkedIn</a> | <a href="https://twitter.com/tu-perfil" target="_blank">Twitter</a></p>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 [Tu Nombre]. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

