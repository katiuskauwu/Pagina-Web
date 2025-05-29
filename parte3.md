<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Préstamos</title>
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
    <h1>Préstamos Activos</h1>
    <p>Aquí puedes revisar los detalles de tus préstamos vigentes y opciones para nuevas solicitudes.</p>

    <h2>Detalles</h2>
    <ul>
        <li><strong>Préstamo Hipotecario</strong>: S/.200,000 a 20 años, tasa 6%.</li>
        <li><strong>Préstamo Vehicular</strong>: S/.50,000 a 5 años, tasa 8%.</li>
    </ul>

    <h2>Simulación de Préstamo</h2>
    <p>Si estás pensando en solicitar un nuevo préstamo, usa esta simulación:</p>
    <p>Monto: S/.100,000 | Plazo: 10 años | Tasa: 7%</p>
    <p><strong>Cuota mensual estimada: S/.1,161</strong></p>

    <h2>Documentos Requeridos</h2>
    <ul>
        <li>DNI vigente</li>
        <li>Últimos 3 recibos de sueldo</li>
        <li>Historial crediticio</li>
    </ul>
</div>
<footer>Katiuska Patilla de la Cruz | Contacto: katiuska@gmail.com | Lima, Perú | Redes: @katiuskaweb</footer>
</body>
</html>
