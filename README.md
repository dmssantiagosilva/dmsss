<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Imagen con Fondo, Margen y Título</title>
<style>
    body {
        margin: 0;
        padding: 0;
        background-image: url('fondo.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        background-attachment: fixed;
    }
    .contenedor-titulo {
        text-align: center;
        margin-top: 10vh; /* Ajusta la posición vertical del título */
        padding: 20px; /* Añadimos un poco de espacio alrededor del título */
        background-color: rgba(0, 0, 0, 0.5); /* Fondo semitransparente */
    }
    h1 {
        font-size: 2.5em; /* Tamaño del título */
        color: white; /* Color del texto */
        margin: 0; /* Eliminamos el margen predeterminado del título */
    }
    .contenedor-imagen {
        text-align: center;
        margin-top: 5vh; /* Ajusta la posición vertical de la imagen */
        position: relative; /* Hacemos que el contenedor de la imagen sea relativo para posicionar el separador */
    }
    .contenedor-imagen img {
        max-width: calc(100% - 40px); /* Reducimos la anchura de la imagen en 40px (20px de margen a cada lado) */
        height: auto;
        margin: 20px; /* Mantenemos el margen de 20px en la parte superior e inferior */
        border-left: 10px solid white; /* Separador a la izquierda de la imagen */
        border-right: 10px solid white; /* Separador a la derecha de la imagen */
    }
</style>
</head>
<body>
    <div class="contenedor-titulo">
        <h1>TECNOMOVIL CENTRO</h1>
    </div>
    <div class="contenedor-imagen">
        <img src="cv1004.jpg" alt="Imagen CV 1004">
    </div>
</body>
</html>
