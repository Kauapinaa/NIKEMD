Esse projeto vai ser direcionada para um "site de vendas online" de perfumes importados.
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Perfumes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .product {
            border: 1px solid #ddd;
            margin: 1em;
            padding: 1em;
            background: #fff;
            text-align: center;
            border-radius: 8px;
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-bottom: 1px solid #ddd;
        }
        .product h2 {
            font-size: 1.5em;
            margin: 0.5em 0;
        }
        .product p {
            font-size: 1em;
            color: #666;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 1em;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Loja de Perfumes</h1>
        </div>
    </header>
    <div class="container">
        <section>
            <div class="product">
                <img src="perfume1.jpg" alt="Perfume Floral">
                <h2>Perfume Floral</h2>
                <p>Descrição: Um perfume fresco e floral, perfeito para o dia a dia.</p>
                <p>Preço: R$ 150,00</p>
                <button>Comprar</button>
            </div>
            <div class="product">
                <img src="perfume2.jpg" alt="Perfume Amadeirado">
                <h2>Perfume Amadeirado</h2>
                <p>Descrição: Um perfume intenso e sofisticado com notas amadeiradas.</p>
                <p>Preço: R$ 200,00</p>
                <button>Comprar</button>
            </div>
            <!-- Adicione mais produtos aqui -->
        </section>
    </div>
    <footer>
        <div class="container">
            <p>&copy; 2024 Loja de Perfumes. Todos os direitos reservados.</p>
        </div>
    </footer>
</body>
</html>
