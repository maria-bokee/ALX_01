# ALX_01
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RGB vs CMYK</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #222;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        section {
            padding: 20px;
            background: #fff;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        img {
            width: 100%;
            max-width: 600px;
            display: block;
            margin: 10px auto;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>RGB vs CMYK</h1>
    </header>
    <div class="container">
        <section>
            <h2>O que é o modelo RGB?</h2>
            <p>O modelo RGB (Red, Green, Blue) é um sistema de cores aditivas usado em telas digitais. As cores são criadas combinando diferentes intensidades dessas três cores primárias.</p>
            <img src="rgb_example.jpg" alt="Exemplo de cores no modelo RGB">
        </section>
        <section>
            <h2>Funcionamento do Pixel no RGB</h2>
            <p>Em telas, cada pixel é composto por subpixels vermelhos, verdes e azuis. A variação de intensidade desses subpixels determina a cor final do pixel.</p>
            <img src="pixel_rgb.jpg" alt="Funcionamento do pixel RGB">
        </section>
        <section>
            <h2>O que é o modelo CMYK?</h2>
            <p>O modelo CMYK (Cyan, Magenta, Yellow, Black) é um sistema de cores subtrativas usado na impressão. Ele funciona subtraindo luz refletida do papel para criar cores.</p>
            <img src="cmyk_example.jpg" alt="Exemplo de cores no modelo CMYK">
        </section>
        <section>
            <h2>Comparação entre RGB e CMYK</h2>
            <p>RGB é ideal para telas, enquanto CMYK é melhor para impressão. A conversão entre os dois modelos pode alterar as cores devido às diferenças nos espaços de cores.</p>
            <img src="rgb_vs_cmyk.jpg" alt="Comparação entre RGB e CMYK">
        </section>
    </div>
</body>
</html>
