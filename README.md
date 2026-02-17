<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Sabores del Mundo</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f4f4;
        }

        header {
            background: linear-gradient(90deg, #4b0082, #6a0dad);
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #2f2f2f;
            display: flex;
            justify-content: center;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            transition: 0.3s;
        }

        nav a:hover {
            color: #d8b4fe;
        }

        .hero {
            text-align: center;
            padding: 60px 20px;
            background-color: white;
        }

        .hero h1 {
            color: #4b0082;
            font-size: 40px;
        }

        .hero p {
            color: #555;
            font-size: 18px;
        }

        .continentes {
            padding: 40px 20px;
            background-color: #e5e5e5;
            text-align: center;
        }

        .continentes h2 {
            color: #4b0082;
        }

        .cards {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .card {
            background-color: white;
            padding: 20px;
            width: 200px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            transition: 0.3s;
        }

        .card:hover {
            transform: scale(1.05);
        }

        .comentarios {
            padding: 50px 20px;
            background-color: white;
            text-align: center;
        }

        .comentarios h2 {
            color: #4b0082;
        }

        form {
            max-width: 500px;
            margin: auto;
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        input, textarea, select {
            padding: 10px;
            border-radius: 8px;
            border: 1px solid #ccc;
            font-size: 14px;
        }

        button {
            background-color: #6a0dad;
            color: white;
            padding: 12px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
            transition: 0.3s;
        }

        button:hover {
            background-color: #4b0082;
        }

        footer {
            background-color: #2f2f2f;
            color: white;
            text-align: center;
            padding: 15px;
            font-size: 14px;
        }
    </style>
</head>

<body>

<header>
    <h1>🌍 Sabores del Mundo</h1>
    <p>Explora recetas auténticas de todos los continentes</p>
</header>

<nav>
    <a href="#">Inicio</a>
    <a href="#">Continentes</a>
    <a href="#">Experiencias</a>
    <a href="#">Registro</a>
</nav>

<section class="hero">
    <h1>Descubre la Cocina Global</h1>
    <p>Un espacio dedicado a las mejores recetas tradicionales del mundo.</p>
</section>

<section class="continentes">
    <h2>🌎 Recetas por Continente</h2>
    <div class="cards">
        <div class="card">🌍 África</div>
        <div class="card">🌎 América</div>
        <div class="card">🌏 Asia</div>
        <div class="card">🌍 Europa</div>
        <div class="card">🌏 Oceanía</div>
    </div>
</section>

<section class="comentarios">
    <h2>⭐ Comparte tu Experiencia</h2>
    <p>Califica tu experiencia en nuestra página y deja tus comentarios.</p>

    <form>
        <input type="text" placeholder="Nombre completo" required>

        <input type="email" placeholder="Correo electrónico" required>

        <input type="tel" placeholder="Número telefónico para registro mensual" required>

        <select required>
            <option value="">Puntuación de la experiencia</option>
            <option value="5">⭐⭐⭐⭐⭐ Excelente</option>
            <option value="4">⭐⭐⭐⭐ Muy Buena</option>
            <option value="3">⭐⭐⭐ Buena</option>
            <option value="2">⭐⭐ Regular</option>
            <option value="1">⭐ Mala</option>
        </select>

        <textarea rows="4" placeholder="Escribe aquí tu comentario..."></textarea>

        <button type="submit">Enviar Comentario</button>
    </form>
</section>

<footer>
    © 2026 Sabores del Mundo | Todos los derechos reservados
</footer>

</body>
</html>
