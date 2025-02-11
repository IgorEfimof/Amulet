<html lang="ru">
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
        .order-container {
            margin-top: 20px;
            text-align: center;
        }
        .order-container img {
            width: 300px;
            margin-top: 20px;
            border-radius: 10px;
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
                <img src="https://i.imgur.com/9dMebEx.jpeg/300x200" alt="Браслет 1" id="bracelet1">
                <h2>Браслет "Сила природы"</h2>
                <p>Ручная работа, натуральные материалы, оберег.</p>
                <p><strong>Цена: 1500 руб.</strong></p>
                <a href="#" class="button" onclick="loadImage('https://via.placeholder.com/300x200')">Заказать</a>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200" alt="Браслет 2" id="bracelet2">
                <h2>Браслет "Защита воина"</h2>
                <p>Мощный оберег для уверенности и силы.</p>
                <p><strong>Цена: 1800 руб.</strong></p>
                <a href="#" class="button" onclick="loadImage('https://via.placeholder.com/300x200')">Заказать</a>
            </div>
            <!-- Другие браслеты -->
        </div>
        <div class="order-container">
            <h3>Вы выбрали:</h3>
            <img id="orderImage" src="" alt="Изображение браслета не выбрано">
        </div>
    </div>

    <script>
        function loadImage(imageUrl) {
            // Заменяем изображение в контейнере на выбранное
            document.getElementById('orderImage').src = imageUrl;
        }
    </script>
</body>
</html>

