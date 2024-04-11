
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Imagen con Fondo y Margen</title>
<style>
    body {
        margin: 0;
        padding: 0;
        background-image: url('fondo.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        background-attachment: fixed;
    }
    .contenedor-imagen {
        text-align: center;
        margin-top: 20vh; /* Ajusta la posición vertical de la imagen */
    }
    .contenedor-imagen img {
        max-width: 100%;
        height: auto;
        margin: 20px; /* Agregamos un margen de 20px a la imagen */
    }
</style>
</head>
<body>
    <div class="contenedor-imagen">
        <img src="cv1004.jpg" alt="Imagen CV 1004">
    </div>
</body>
</html>
