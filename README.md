# -index.html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página con Imágenes de Fondo y Texto</title>
    <style>
        body, html {
            height: 100%;
            margin: 0;
            font-family: Arial, sans-serif;
        }
        .section {
            position: relative;
            width: 100%;
            height: 100vh;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            padding: 20px;
            box-sizing: border-box;
        }
        .content {
            background-color: rgba(0, 0, 0, 0.5); /* Fondo semitransparente para mayor legibilidad */
            padding: 20px;
            border-radius: 10px;
        }
        h1 {
            margin: 0 0 20px;
        }
        h2 {
            margin: 0 0 10px;
        }
        a {
            color: white;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="section" style="background-image: url('https://i.ibb.co/XSpLDCV/Imagen-de-Whats-App-2024-06-11-a-las-16-29-09-9cfa6e12.jpg');">
        <div class="content">
            <h1>Bienvenidos a Viajes Leonardo</h1>
            <p>Descubre el mundo con nosotros y vive experiencias inolvidables.</p>
        </div>
    </div>
    
    <div class="section" style="background-image: url('https://i.ibb.co/P9RfmSz/Imagen-de-Whats-App-2024-06-11-a-las-16-29-09-01232991.jpg');">
        <div class="content">
            <h2>Paquetes de Cancún</h2>
            <a href="https://ibb.co/D8NSVqg" target="_blank">Ver más</a>
        </div>
    </div>
    
    <div class="section" style="background-image: url('https://i.ibb.co/P9RfmSz/Imagen-de-Whats-App-2024-06-11-a-las-16-29-09-01232991.jpg');">
        <div class="content">
            <h2>Paquetes en Los Cabos</h2>
            <a href="https://ibb.co/D8NSVqg" target="_blank">Ver más</a>
        </div>
    </div>
    
    <div class="section" style="background-image: url('https://i.ibb.co/P9RfmSz/Imagen-de-Whats-App-2024-06-11-a-las-16-29-09-01232991.jpg');">
        <div class="content">
            <h2>Paquetes de Nayarit</h2>
            <a href="https://ibb.co/D8NSVqg" target="_blank">Ver más</a>
        </div>
    </div>
    
    <!-- Espacio para agregar más secciones con imágenes -->
    <div class="section" style="background-image: url('https://i.ibb.co/P9RfmSz/Imagen-de-Whats-App-2024-06-11-a-las-16-29-09-01232991.jpg');">
        <div class="content">
            <h2>Nuevo Paquete</h2>
            <a href="https://ibb.co/D8NSVqg" target="_blank">Ver más</a>
        </div>
    </div>
</body>
</html>
