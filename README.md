<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Casa Rural Babia - Finlandón y Calecho</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-image: url('https://example.com/montañas.jpg'); /* Imagen de las montañas */
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 100px 20px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
        }
        header h1 {
            font-size: 3em;
            margin: 0;
        }
        header p {
            font-size: 1.5em;
        }
        nav {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.2em;
        }
        section {
            padding: 50px 20px;
            max-width: 1000px;
            margin: auto;
        }
        .casa {
            margin-bottom: 30px;
        }
        .casa h2 {
            font-size: 2em;
            margin-bottom: 10px;
            color: #333;
        }
        .casa p {
            font-size: 1.2em;
            color: #666;
        }
        .activities {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 30px;
        }
        .activity {
            background-color: #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            width: 250px;
        }
        .activity img {
            max-width: 100%;
            border-radius: 10px;
        }
        .activity h3 {
            font-size: 1.5em;
            margin-bottom: 10px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .contacto {
            margin-bottom: 20px;
        }
        .contacto h3 {
            font-size: 1.2em;
            margin-bottom: 5px;
        }
        .contacto a {
            color: #4caf50;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <h1>Casa Rural en Babia - Finlandón y Calecho</h1>
        <p>Vive la montaña como nunca antes</p>
    </header>

    <nav>
        <a href="#casas">Casas</a>
        <a href="#actividades">Actividades</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section id="casas">
        <h2>Nuestras Casas</h2>
        <div class="casa">
            <h2>Casa Finlandón</h2>
            <p>Una casa acogedora con vistas espectaculares de las montañas de Babia. Ideal para familias y grupos pequeños.</p>
        </div>
        <div class="casa">
            <h2>Casa Calecho</h2>
            <p>Un refugio perfecto para quienes buscan desconectar. Rodeada de naturaleza, ofrece tranquilidad absoluta.</p>
        </div>
    </section>

    <section id="actividades">
        <h2>Actividades en el Entorno</h2>
        <div class="activities">
            <div class="activity">
                <img src="https://example.com/senderismo.jpg" alt="Senderismo">
                <h3>Senderismo</h3>
                <p>Explora rutas de montaña impresionantes, desde paseos suaves hasta desafíos para aventureros.</p>
            </div>
            <div class="activity">
                <img src="https://example.com/pesca.jpg" alt="Pesca">
                <h3>Pesca</h3>
                <p>Disfruta de la pesca en los ríos y lagos cercanos. Relájate en plena naturaleza.</p>
            </div>
            <div class="activity">
                <img src="https://example.com/caballos.jpg" alt="Paseos a caballo">
                <h3>Paseos a Caballo</h3>
                <p>Descubre el paisaje a lomos de un caballo, una experiencia inolvidable para todas las edades.</p>
            </div>
        </div>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <div class="contacto">
            <h3>Email:</h3>
            <a href="mailto:info@casaruralbabia.com">info@casaruralbabia.com</a>
        </div>
        <div class="contacto">
            <h3>Teléfono:</h3>
            <a href="tel:+34987654321">+34 987 654 321</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Casa Rural Babia - Finlandón y Calecho | Todos los derechos reservados</p>
    </footer>
</body>
</html>
