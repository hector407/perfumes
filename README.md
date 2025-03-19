<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo de Perfumes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            text-align: center;
        }
        .catalogo {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .producto {
            border: 1px solid #ddd;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
        }
        .producto img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .boton-comprar {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background-color: #ff4081;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <h1>Perfumes Victoria S.</h1>
    <div class="catalogo">
        <div class="producto">
            <img src="descarga.jpg" alt="Perfume Elegante">
            <h3>Perfume Elegante</h3>
            <p>Aroma floral y fresco, ideal para cualquier ocasión.</p>
            <p><strong>$335 MX</strong></p>
            <a href="#" class="boton-comprar">Comprar</a>
        </div>
        <div class="producto">
            <img src="descarga (1).jpg" alt="Perfume Intenso">
            <h3>Perfume Intenso</h3>
            <p>Notas amaderadas con toques de vainilla, para una presencia inolvidable.</p>
            <p><strong>$439 MX</strong></p>
            <a href="#" class="boton-comprar">Comprar</a>
        </div>
        <div class="producto">
            <img src="descarga (2).jpg" alt="Perfume Sofisticado">
            <h3>Perfume Sofisticado</h3>
            <p>Aroma cítrico y especiado, perfecto para el día a día.</p>
            <p><strong>$1,885 MX</strong></p>
            <a href="#" class="boton-comprar">Comprar</a>
        </div>
    </div>
</body>
</html>
