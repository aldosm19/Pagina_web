<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Bienvenido Contribuyente</title>
    <style>
        body {
            background-color: #0000FF; /* Color de fondo azul */
            color: white; /* Color de texto */
            font-family: Arial, sans-serif; /* Tipo de fuente */
            padding: 20px; /* Espaciado interno */
        }
        .container {
            max-width: 600px; /* Ancho máximo del contenedor */
            margin: auto; /* Centrado horizontal */
            background-color: #3333FF; /* Color de fondo del contenedor */
            padding: 20px; /* Espaciado interno del contenedor */
            border-radius: 8px; /* Bordes redondeados */
            box-shadow: 0 0 10px rgba(0,0,0,0.5); /* Sombra alrededor del contenedor */
        }
        input[type="text"], input[type="email"] {
            width: 100%; /* Ancho del campo de texto */
            padding: 10px; /* Espaciado interno del campo de texto */
            margin-top: 5px; /* Espacio superior del campo de texto */
            margin-bottom: 20px; /* Espacio inferior del campo de texto */
            border: none; /* Sin borde */
            border-radius: 4px; /* Bordes redondeados */
        }
        label {
            font-weight: bold; /* Negrita para las etiquetas */
        }
        .btn-submit {
            background-color: #00AEEF; /* Color de fondo del botón */
            color: white; /* Color de texto del botón */
            padding: 10px 20px; /* Espaciado interno del botón */
            border: none; /* Sin borde */
            border-radius: 4px; /* Bordes redondeados */
            cursor: pointer; /* Puntero al pasar sobre el botón */
            font-size: 16px; /* Tamaño de fuente */
        }
        .btn-submit:hover {
            background-color: #007B9A; /* Color de fondo del botón al pasar el cursor */
        }
        .contact-info {
            margin-top: 20px; /* Espacio superior */
            padding: 10px; /* Espaciado interno */
            background-color: #4444FF; /* Color de fondo */
            border-radius: 8px; /* Bordes redondeados */
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Bienvenido Contribuyente</h1>
        <p>
            Debido a que hemos detectado algunas inconsistencias en nuestras bases de datos, te pedimos de la forma más atenta poder llenar el siguiente cuestionario, si no tienes información a la mano, no te preocupes. Podemos ayudarte en nuestras oficinas ubicadas en Avenida Morelo 25, Centro. O llamando al número 5523231010
        </p>
        <form>
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" required>
            
            <button type="submit" class="btn-submit">Enviar</button>
        </form>
        <div class="contact-info">
            <p>Visítanos en nuestras oficinas:</p>
            <p>Avenida Morelo 25, Centro</p>
            <p>Llama al: 5523231010</p>
        </div>
    </div>
</body>
</html>
