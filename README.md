<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            margin: 0;
        }

        header {
            background-color: #0078D7;
            color: white;
            padding: 20px;
        }

        main {
            padding: 30px;
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #0078D7;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background-color: #005fa3;
        }
    </style>
</head>
<body>

<header>
    <h1>¡Bienvenido a mi página web!</h1>
</header>

<main>
    <p>Esta es mi primera página web.</p>
    <button onclick="saludar()">Haz clic aquí</button>
</main>

<script>
function saludar() {
    alert("¡Hola! Gracias por visitar mi página.");
}
</script>

</body>
</html>