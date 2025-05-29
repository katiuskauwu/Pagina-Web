<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Historial Financiero</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-image: url(fondo\ imagen.jpg);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .sidebar {
            position: fixed;
            width: 220px;
            height: 100%;
            background-color: #343a40;
            color: #fff;
            padding-top: 20px;
        }
        .sidebar a {
            display: block;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
        }
        .sidebar a:hover {
            background-color: #495057;
            border-radius: 5px;
        }
        .content {
            margin-left: 240px;
            padding: 20px;
            max-width: 1000px;
        }
        footer {
            background-color: #343a40;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
        h1, h2 {
            text-align: center;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
<div class="sidebar">
    <h2 class="text-center">Menú</h2>
    <a href="index.html">Inicio</a>
    <a href="historia.html">Historia</a>
    <a href="prestamos.html">Préstamos</a>
</div>
<div class="content">
    <h1>Historia Financiera</h1>
    <p>Aquí puedes consultar todos tus movimientos bancarios desde el inicio de tu cuenta.</p>

    <h2>Movimientos Recientes</h2>
    <ul>
        <li>Depósito de S/.5,000 el 12/03/2025</li>
        <li>Pago de tarjeta de crédito S/.1,200 el 20/03/2025</li>
        <li>Retiro en efectivo S/.500 el 25/03/2025</li>
    </ul>

    <h2>Tabla de Operaciones</h2>
    <table class="table table-striped">
        <thead><tr><th>Fecha</th><th>Descripción</th><th>Monto</th></tr></thead>
        <tbody>
            <tr><td>01/02/2025</td><td>Pago hipoteca</td><td>-S/.2,500</td></tr>
            <tr><td>15/02/2025</td><td>Ingreso nómina</td><td>+S/.8,000</td></tr>
            <tr><td>28/02/2025</td><td>Compra supermercado</td><td>-S/.400</td></tr>
        </tbody>
    </table>

    <h2>Reflexiones</h2>
    <p>Tu historial muestra un buen control financiero. No olvides revisar tus movimientos cada semana para mantenerte al día y detectar cualquier irregularidad.</p>
</div>
<footer>Katiuska Patilla de la Cruz | Contacto: katiuska@gmail.com | Lima, Perú | Redes: @katiuskaweb</footer>
</body>
</html>
