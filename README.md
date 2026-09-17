```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo de Autos</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f2f2f2;
            color: #222;
        }

        header {
            background-color: #111;
            color: white;
            text-align: center;
            padding: 30px;
        }

        header h1 {
            font-size: 35px;
            margin-bottom: 10px;
        }

        header p {
            color: #ccc;
        }

        .contenedor {
            display: flex;
            justify-content: center;
            gap: 30px;
            padding: 50px 20px;
            flex-wrap: wrap;
        }

        .auto {
            background-color: white;
            width: 350px;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.15);
            transition: transform 0.3s;
        }

        .auto:hover {
            transform: translateY(-8px);
        }

        .auto img {
            width: 100%;
            height: 220px;
            object-fit: cover;
        }

        .informacion {
            padding: 25px;
            text-align: center;
        }

        .informacion h2 {
            margin-bottom: 10px;
            font-size: 24px;
        }

        .informacion p {
            color: #666;
            margin-bottom: 20px;
            line-height: 1.5;
        }

        .precio {
            font-size: 22px;
            font-weight: bold;
            margin-bottom: 20px;
        }

        .boton {
            display: inline-block;
            background-color: #111;
            color: white;
            text-decoration: none;
            padding: 12px 25px;
            border-radius: 8px;
            transition: background-color 0.3s;
        }

        .boton:hover {
            background-color: #444;
        }

        footer {
            background-color: #111;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>

<body>

    <header>
        <h1>🚗 Catálogo de Autos</h1>
        <p>Conoce nuestros vehículos disponibles</p>
    </header>

    <section class="contenedor">

        <!-- AUTO 1 -->
        <div class="auto">
            <img src="img/auto1.jpg" alt="Auto deportivo">

            <div class="informacion">
                <h2>BMW Serie 3</h2>

                <p>
                    Automóvil moderno, cómodo y potente,
                    ideal para viajes y uso diario.
                </p>

                <div class="precio">$35.000</div>

                <a href="#" class="boton">Ver detalles</a>
            </div>
        </div>

        <!-- AUTO 2 -->
        <div class="auto">
            <img src="img/auto2.jpg" alt="Auto moderno">

            <div class="informacion">
                <h2>Toyota Corolla</h2>

                <p>
                    Vehículo económico, seguro y confiable,
                    perfecto para la ciudad.
                </p>

                <div class="precio">$25.000</div>

                <a href="#" class="boton">Ver detalles</a>
            </div>
        </div>

    </section>

    <footer>
        <p>© 2026 Catálogo de Autos | Mi página web</p>
    </footer>

</body>
</html>
```
