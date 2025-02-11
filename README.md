<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Магазин Браслетов</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f8f8f8;
            padding: 20px;
            margin: 0;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }
        .product {
            background: #fff;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }
        .product img {
            width: 100%;
            border-radius: 10px;
            max-width: 300px;
            height: auto;
        }
        .button {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background: #ff5733;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        @media (max-width: 768px) {
            .products {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Стильные Плетеные Браслеты</h1>
        <div class="products">
            <div class="product">
                <img src="https://i.imgur.com/9dMebEx.jpeg/300x200" alt="Браслет 1">
                <h2>Браслет "Сила природы"</h2>
                <p>Ручная работа, натуральные материалы, оберег.</p>
                <p><strong>Цена: 1500 руб.</strong></p>
                <a href="https://t.me/IgEfR" class="button">Заказать</a>
         </div>
            <div class="product">
                <img src="https://i.imgur.com/E7bluXe.jpeg/300x200" alt="Браслет 2">
                <h2>Браслет "Защита воина"</h2>
                <p>Мощный оберег для уверенности и силы.</p>
                <p><strong>Цена: 1800 руб.</strong></p>
                <a href="https://t.me/IgEfR" class="button">Заказать</a>
            </div>
            <div class="product">
                <img src="https://i.imgur.com/STeB3WV.jpeg/300x200" alt="Браслет 3">
                <h2>Браслет "Энергия земли"</h2>
                <p>Сила природы в каждой нити.</p>
                <p><strong>Цена: 1700 руб.</strong></p>
                <a href="https://t.me/IgEfR" class="button">Заказать</a>
            </div>
            <div class="product">
                <img src="https://i.imgur.com/NN5a7Nq.jpeg/300x200" alt="Браслет 4">
                <h2>Браслет "Огонь души"</h2>
                <p>Талисман страсти и решимости.</p>
                <p><strong>Цена: 1600 руб.</strong></p>
                <a href="https://t.me/IgEfR" class="button">Заказать</a>
            </div>
            <div class="product">
                <img src="https://i.imgur.com/HgEqRve.jpeg/300x200" alt="Браслет 5">
                <h2>Браслет "Лунный свет"</h2>
                <p>Мягкость и гармония в каждом движении.</p>
                <p><strong>Цена: 1400 руб.</strong></p>
                <a href="https://t.me/IgEfR" class="button">Заказать</a>
            </div>
            <div class="product">
                <img src="https://i.imgur.com/10OSV2Z.jpeg/300x200" alt="Браслет 6">
                <h2>Браслет "Сила духа"</h2>
                <p>Помогает сохранять уверенность и стойкость.</p>
                <p><strong>Цена: 1900 руб.</strong></p>
                <a href="https://t.me/IgEfR" class="button">Заказать</a>
            </div>
        </div>
    </div>
</body>
