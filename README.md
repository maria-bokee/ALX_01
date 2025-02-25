<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RGB e CMYK: Diferenças e Aplicações</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e3e3e3;
            color: #222;
        }
        .container {
            width: 90%;
            max-width: 1000px;
            margin: auto;
            padding: 20px;
        }
        header {
            background: linear-gradient(to right, #ff4e50, #1e90ff);
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
        }
        section {
            background: white;
            padding: 20px;
            margin-top: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        img {
            width: 100%;
            max-width: 500px;
            display: block;
            margin: 15px auto;
            border-radius: 8px;
        }
        .highlight {
            font-weight: bold;
            color: #ff4e50;
        }
    </style>
</head>
<body>
    <header>
        RGB e CMYK: Diferenças e Aplicações
    </header>
    <div class="container">
        <section>
            <h2>Modelo RGB: Como Funciona?</h2>
            <p>RGB (<span class="highlight">Red, Green, Blue</span>) é um modelo de cores aditivas utilizado em telas digitais. A combinação dessas três cores em diferentes intensidades cria a vasta gama de cores visíveis nos dispositivos eletrônicos.</p>
            <img src="https://pederpan.github.io/computacao-grafica/assets/rgb_example.jpg" alt="Esquema de cores RGB">
        </section>
        <section>
            <h2>Pixels e RGB</h2>
            <p>Cada pixel de uma tela é composto por três subpixels: um vermelho, um verde e um azul. A variação da intensidade desses subpixels gera diferentes cores, permitindo imagens vibrantes e detalhadas.</p>
            <img src="https://pederpan.github.io/computacao-grafica/assets/pixel_rgb.jpg" alt="Estrutura do pixel RGB">
        </section>
        <section>
            <h2>Modelo CMYK: Impressão e Cores</h2>
            <p>O modelo <span class="highlight">CMYK</span> (<span class="highlight">Cyan, Magenta, Yellow, Black</span>) é usado em impressões. Diferente do RGB, que adiciona luz para formar cores, o CMYK funciona removendo luz refletida do papel.</p>
            <img src="https://pederpan.github.io/computacao-grafica/assets/cmyk_example.jpg" alt="Esquema de cores CMYK">
        </section>
        <section>
            <h2>RGB vs CMYK: Qual a Diferença?</h2>
            <p>RGB é ideal para <span class="highlight">telas digitais</span>, enquanto CMYK é usado para <span class="highlight">materiais impressos</span>. A conversão entre os dois pode gerar diferenças de cor, pois cada modelo possui um espectro de cores distinto.</p>
            <img src="https://pederpan.github.io/computacao-grafica/assets/rgb_vs_cmyk.jpg" alt="Comparação entre RGB e CMYK">
        </section>
    </div>
</body>
</html>
