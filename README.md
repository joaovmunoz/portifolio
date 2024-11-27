!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .hero {
            background: url('images/bg.jpg') no-repeat center center;
            background-size: cover;
            height: 100vh;
            position: relative;
        }
        .hero-overlay {
            background: url('images/overlay.png') repeat;
            height: 100vh;
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
        }
        .gallery {
            display: flex;
            gap: 10px;
            padding: 20px;
        }
        .gallery img {
            width: 30%;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <!-- Seção de Hero -->
    <div class="hero">
        <div class="hero-overlay"></div>
    </div>

    <!-- Seção de Galeria -->
    <section class="gallery">
        <img src="images/pic01.jpg" alt="Imagem 1">
        <img src="images/pic02.jpg" alt="Imagem 2">
        <img src="images/pic03.jpg" alt="Imagem 3">
    </section>
</body>
</html>
