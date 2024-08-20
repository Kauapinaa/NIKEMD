<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Moda</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        .container {
            padding: 20px;
        }
        .product-section {
            margin-bottom: 30px;
        }
        .product-section h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
        }
        .product-item {
            display: inline-block;
            width: 30%;
            box-sizing: border-box;
            padding: 10px;
        }
        .product-item img {
            max-width: 100%;
            height: auto;
        }
        .product-item h3 {
            font-size: 1.2em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Loja de Moda</h1>
        <nav>
            <ul>
                <li><a href="#roupas">Roupas</a></li>
                <li><a href="#tenis">Tênis</a></li>
                <li><a href="#relógios">Relógios</a></li>
                <li><a href="#bermudas">Bermudas</a></li>
            </ul>
        </nav>
    </header>
    <div class="container">
        <section id="roupas" class="product-section">
            <h2>Roupas</h2>
            <div class="product-item">
                <img src="roupa1.jpg" alt="Roupa 1">
                <h3>Camiseta</h3>
                <p>R$ 99,90</p>
            </div>
            <div class="product-item">
                <img src="roupa2.jpg" alt="Roupa 2">
                <h3>Jaqueta Jeans</h3>
                <p>R$ 149,90</p>
            </div>
            <!-- Adicione mais itens conforme necessário -->
        </section>
        <section id="tenis" class="product-section">
            <h2>Tênis</h2>
            <div class="product-item">
                <img src="tenis1.jpg" alt="Tênis 1">
                <h3>Tênis Esportivo</h3>
                <p>R$ 199,90</p>
            </div>
            <div class="product-item">
                <img src="tenis2.jpg" alt="Tênis 2">
                <h3>Tênis Casual</h3>
                <p>R$ 159,90</p>
            </div>
            <!-- Adicione mais itens conforme necessário -->
        </section>
        <section id="relógios" class="product-section">
            <h2>Relógios</h2>
            <div class="product-item">
                <img src="relogio1.jpg" alt="Relógio 1">
                <h3>Relógio Clássico</h3>
                <p>R$ 299,90</p>
            </div>
            <div class="product-item">
                <img src="relogio2.jpg" alt="Relógio 2">
                <h3>Relógio Esportivo</h3>
                <p>R$ 249,90</p>
            </div>
            <!-- Adicione mais itens conforme necessário -->
        </section>
        <section id="bermudas" class="product-section">
            <h2>Bermudas</h2>
            <div class="product-item">
                <img src="bermuda1.jpg" alt="Bermuda 1">
                <h3>Bermuda de Sarja</h3>
                <p>R$ 89,90</p>
            </div>
            <div class="product-item">
                <img src="bermuda2.jpg" alt="Bermuda 2">
                <h3>Bermuda Jeans</h3>
                <p>R$ 109,90</p>
            </div>
            <!-- Adicione mais itens conforme necessário -->
        </section>
    </div>
</body>
</html>
