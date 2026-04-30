# atividade-programa-o-web.lele-e-madu Atividade da Aluna Maria Eduarda e Leticia Vicente


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Pizzaria Mineira</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff8f0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #8B0000;
            color: white;
            text-align: center;
            padding: 20px;
        }
        h1 {
            margin: 0;
        }
        .container {
            padding: 20px;
        }
        .categoria {
            margin-bottom: 30px;
        }
        .categoria h2 {
            color: #8B0000;
            border-bottom: 2px solid #8B0000;
            padding-bottom: 5px;
        }
        .item {
            display: flex;
            justify-content: space-between;
            margin: 8px 0;
        }
        .preco {
            font-weight: bold;
        }
        footer {
            text-align: center;
            background-color: #8B0000;
            color: white;
            padding: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>🍕 Pizzaria Mineira</h1>
    <p>Sabor de Minas em cada fatia!</p>
</header>

<div class="container">

    <div class="categoria">
        <h2>Pizzas Tradicionais</h2>
        <div class="item">
            <span>Mussarela</span>
            <span class="preco">R$ 35,00</span>
        </div>
        <div class="item">
            <span>Calabresa</span>
            <span class="preco">R$ 38,00</span>
        </div>
        <div class="item">
            <span>Frango com Catupiry</span>
            <span class="preco">R$ 40,00</span>
        </div>
    </div>

    <div class="categoria">
        <h2>Pizzas Especiais</h2>
        <div class="item">
            <span>Mineira (Queijo, milho e bacon)</span>
            <span class="preco">R$ 45,00</span>
        </div>
        <div class="item">
            <span>Quatro Queijos</span>
            <span class="preco">R$ 42,00</span>
        </div>
        <div class="item">
            <span>Portuguesa</span>
            <span class="preco">R$ 44,00</span>
        </div>
    </div>

    <div class="categoria">
        <h2>Bebidas</h2>
        <div class="item">
            <span>Refrigerante Lata</span>
            <span class="preco">R$ 6,00</span>
        </div>
        <div class="item">
            <span>Suco Natural</span>
            <span class="preco">R$ 8,00</span>
        </div>
        <div class="item">
            <span>Água</span>
            <span class="preco">R$ 4,00</span>
        </div>
    </div>

</div>

<footer>
    <p>📍 Rua da Araras, 123 | 📞 (84) 3758-867587</p>
</footer>

</body>
</html>
