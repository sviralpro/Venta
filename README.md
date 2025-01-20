<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ViralPro - Contáctame</title>
    <style>
        /* Estilos generales */
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            color: #fff;
            background: linear-gradient(135deg, #1f1f1f, #000) no-repeat;
        }
        /* Encabezado */
        header {
            background: #121212;
            padding: 20px;
            text-align: center;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.7);
        }
        header h1 {
            font-size: 2.5rem;
            letter-spacing: 3px;
            margin: 0;
        }
        /* Formulario */
        .contact-container {
            margin: 40px auto;
            padding: 30px;
            max-width: 600px;
            background: rgba(255, 255, 255, 0.05);
            box-shadow: 0px 4px 20px rgba(0, 255, 255, 0.5);
            border-radius: 10px;
        }
        .contact-container h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        form label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: none;
            border-radius: 5px;
            background: #333;
            color: #fff;
        }
        form input[type="submit"] {
            background: #00c3ff;
            color: #000;
            font-weight: bold;
            cursor: pointer;
        }
        form input[type="submit"]:hover {
            background: #00ff77;
        }
        /* Pie de página */
        footer {
            text-align: center;
            padding: 20px;
            background: #121212;
            font-size: 0.9rem;
            border-top: 1px solid #333;
        }
    </style>
</head>
<body>
    <!-- Encabezado -->
    <header>
        <h1>Bienvenidos a ViralPro</h1>
        <p>¡Aquí podrás contactarme fácilmente!</p>
    </header>

    <!-- Formulario de contacto -->
    <section class="contact-container">
        <h2>Escríbeme</h2>
        <form action="sviralpro@gmail.com" method="POST" enctype="text/plain">
            <label for="name">Tu Nombre</label>
            <input type="text" id="name" name="name" placeholder="Escribe tu nombre" required>
            
            <label for="email">Tu Correo</label>
            <input type="email" id="email" name="email" placeholder="Escribe tu correo" required>
            
            <label for="message">Mensaje</label>
            <textarea id="message" name="message" rows="5" placeholder="Escribe tu mensaje aquí" required></textarea>
            
            <input type="submit" value="Enviar">
        </form>
    </section>

    <!-- Pie de página -->
    <footer>
        &copy; 2022 ViralPro. Todos los derechos reservados.
    </footer>
</body>
</html>
