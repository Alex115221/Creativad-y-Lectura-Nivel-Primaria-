# Creativad-y-Lectura-Nivel-Primaria-
Clase semestral
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menú Interactivo</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="menu">
        <ul>
            <li><a href="#" onclick="mostrarContenido('inicio')">Inicio</a></li>
            <li><a href="#" onclick="mostrarContenido('servicios')">Servicios</a></li>
            <li><a href="#" onclick="mostrarContenido('acerca')">Acerca de</a></li>
            <li><a href="#" onclick="mostrarContenido('contacto')">Contacto</a></li>
        </ul>
    </div>

    <div id="contenido" class="contenido">
        <h2>Bienvenido a la página de inicio</h2>
        <p>Selecciona una opción del menú para ver más información.</p>
    </div>

    <script src="script.js"></script>
</body>
</html>
