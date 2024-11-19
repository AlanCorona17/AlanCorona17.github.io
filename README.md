READ ME








<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio de Alan Michelle Corona Cruz</title>
    <style>
        /* Estilos básicos */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background: linear-gradient(to bottom right, #8e44ad, #3498db);
            color: #f4f4f4;
            min-height: 100vh;
        }

        header, footer {
            height: 100vh; 
            margin: 0;
            background: linear-gradient(to right, #8e44ad, #3498db);
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #ffffff;
        }

        nav {
            background: linear-gradient(to right, #2c3e50, #2980b9);
            padding: 0.5rem;
            text-align: center;
            border-radius: 8px;
            display: flex;
            justify-content: center;
            gap: 1rem; /* Espacio entre botones */
        }

        nav a {
            color: #ffffff;
            margin: 0;
            padding: 12px 20px;
            text-decoration: none;
            border-radius: 8px;
            background: linear-gradient(to right, #1abc9c, #2ecc71);
            transition: all 0.4s ease-in-out;
            font-weight: bold;
            position: relative;
            overflow: hidden;
            display: inline-block;
        }

        nav a::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: rgba(255, 255, 255, 0.2);
            transition: left 0.4s;
            z-index: 0;
        }

        nav a:hover::before {
            left: 0;
        }

        nav a:hover {
            background: linear-gradient(to right, #27ae60, #2ecc71);
            transform: translateY(-3px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
            z-index: 1;
        }

        section {
            padding: 1rem;
            margin: 1rem auto;
            max-width: 800px;
            background: rgba(0, 0, 0, 0.5);
            border-radius: 12px;
        }

        .project {
            margin-bottom: 1.5rem;
        }

        .project img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            color: white;
            text-align: center;
            text-decoration: none;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.4s ease-in-out;
            position: relative;
            overflow: hidden;
        }

        .btn::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: rgba(255, 255, 255, 0.2);
            transition: left 0.4s;
            z-index: 1;
        }

        .btn:hover::before {
            left: 100%;
        }

        .btn-email {
            background: linear-gradient(to right, #16a085, #f4d03f);
        }

        .btn-email:hover {
            background: linear-gradient(to right, #0e6655, #f7dc6f);
            transform: translateY(-3px);
        }

        .btn-linkedin {
            background: linear-gradient(to right, #0077b5, #85c1e9);
        }

        .btn-linkedin:hover {
            background: linear-gradient(to right, #005582, #73a9c2);
            transform: translateY(-3px);
        }

        li {
            list-style: none;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Portafolio de Alan Michelle Corona Cruz</h1>
        <p>Ser Eficiente y Concreto es mi base</p>
    </header>

    <nav>
        <a href="#sobre-mi">Sobre Mí</a>
        <a href="#proyectos">Proyectos</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <main>
        <section id="sobre-mi">
            <h2>Sobre Mí</h2>
            <p>Hola, soy Alan Corona, estudiante de Ingeniería en Sistemas Computacionales y Electrónicos. Me apasiona la programación y siempre busco nuevos desafíos para aprender y mejorar.</p>
        </section>

        <section id="proyectos">
            <h2>Proyectos</h2>
            <div class="project">
                <h3>Proyecto 1: Sensor de Proximidad Con Buzzer y Leds</h3>
                <p>Cree un sensor de proximidad con Arduino que detecta la distancia de un objeto o persona. Desde 10 cm a 15 cm se enciende el led verde, entre 6 y 10 cm el led naranja, y desde 0 a 5 cm el led rojo y se emite un pitido.</p>
                <img src="ruta/a/sensor.jpg" alt="Imagen del Proyecto 1">
            </div>
        </section>

        <section id="contacto">
            <h2>Contacto</h2>
            <ul>
                <li>
                    <a href="mailto:amcorona17@gmail.com" class="btn btn-email">Email: alanmcorona17@gmail.com</a>
                </li>
                <li>
                    <a href="https://www.linkedin.com/in/alan-michelle-corona-cruz-057994330/" target="_blank" class="btn btn-linkedin">LinkedIn</a>
                </li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Alan. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
