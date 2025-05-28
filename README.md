<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dibujo Arquitectónico y Construcción - COBAEP</title>
    
    <style>
        /* Estilo general */
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        /* Encabezado */
        header {
            background-color: #3f51b5;
            color: white;
            padding: 20px;
        }

        /* Contenedor general */
        .container {
            width: 80%;
            margin: auto;
        }

        /* Secciones */
        .section {
            padding: 20px;
            margin: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
        }

        /* Módulos interactivos */
        .modulo {
            background: #3f51b5;
            color: white;
            padding: 15px;
            margin: 10px;
            border-radius: 5px;
            font-weight: bold;
            cursor: pointer;
        }

        /* Pie de página */
        footer {
            background-color: #3f51b5;
            color: white;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>¡Construye tu futuro con COBAEP!</h1>
        <p>Descubre la capacitación en Dibujo Arquitectónico y Construcción</p>
    </header>

    <div class="container">
        <div class="section">
            <h2>Ubicaciones de COBAEP</h2>
            <p>Haz clic en un módulo para ver la ubicación.</p>
            
            <div class="modulo" onclick="abrirUbicacion('file:///C:/Users/ab210/OneDrive/Escritorio/pagina%20web.html')">COBAEP Plantel 26</div>
            <div class="modulo" onclick="abrirUbicacion('https://maps.google.com/?q=19.0501,-98.2105')">COBAEP Plantel 12</div>
            <div class="modulo" onclick="abrirUbicacion('https://maps.google.com/?q=19.0331,-98.2227')">COBAEP Plantel 8</div>
        </div>
    </div>

    <footer>
        <p>¿Interesado? Contáctanos para más información.</p>
    </footer>

    <script>
        function abrirUbicacion(url) {
            window.open(url, '_blank');
        }
    </script>
</body>
</html>
