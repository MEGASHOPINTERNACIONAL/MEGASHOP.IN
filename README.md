<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proyectos Personales</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #003366;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        header p {
            margin: 0;
            font-size: 1.2em;
        }

        .container {
            width: 80%;
            margin: 20px auto;
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .project {
            border-bottom: 1px solid #ccc;
            padding: 10px 0;
        }

        .project:last-child {
            border-bottom: none;
        }

        .project h2 {
            margin: 0;
            color: #003366;
        }

        .project p {
            margin: 5px 0;
            color: #666;
        }

        .project .date {
            font-size: 0.9em;
            color: #999;
        }

        .project .tech {
            font-size: 0.9em;
            color: #0066cc;
        }

        .project a {
            color: #0066cc;
            text-decoration: none;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #003366;
            color: #fff;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Proyectos Personales</h1>
        <p>Una colección de mis proyectos más destacados</p>
    </header>

    <div class="container">
        <!-- Proyecto 1 -->
        <div class="project">
            <h2>Proyecto 1: Título del Proyecto</h2>
            <p class="date">Fecha: Junio 2024</p>
            <p class="tech">Tecnologías: HTML, CSS, JavaScript</p>
            <p>Descripción: Breve descripción del proyecto, lo que se logró, y cualquier detalle relevante.</p>
            <p><a href="https://enlace-al-proyecto.com" target="_blank">Ver Proyecto</a></p>
        </div>
        
        <!-- Proyecto 2 -->
        <div class="project">
            <h2>Proyecto 2: Título del Proyecto</h2>
            <p class="date">Fecha: Mayo 2024</p>
            <p class="tech">Tecnologías: Python, Flask</p>
            <p>Descripción: Breve descripción del proyecto, lo que se logró, y cualquier detalle relevante.</p>
            <p><a href="https://enlace-al-proyecto.com" target="_blank">Ver Proyecto</a></p>
        </div>
        
        <!-- Proyecto 3 -->
        <div class="project">
            <h2>Proyecto 3: Título del Proyecto</h2>
            <p class="date">Fecha: Abril 2024</p>
            <p class="tech">Tecnologías: React, Node.js</p>
            <p>Descripción: Breve descripción del proyecto, lo que se logró, y cualquier detalle relevante.</p>
            <p><a href="https://enlace-al-proyecto.com" target="_blank">Ver Proyecto</a></p>
        </div>
    </div>

    <footer>
        <p>© 2024 Tu Nombre. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
