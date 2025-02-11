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
                <a href="#" class="button" onclick="loadImageAndOpenTelegram(event, 'Браслет "Сила природы"', 'https://i.imgur.com/9dMebEx.jpeg/300x200', 'https://t.me/IgEfR')">Заказать</a>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200" alt="Браслет 2" id="bracelet2">
                <h2>Браслет "Защита воина"</h2>
                <p>Мощный оберег для уверенности и силы.</p>
                <p><strong>Цена: 1800 руб.</strong></p>
                <a href="#" class="button" onclick="loadImageAndOpenTelegram(event, 'Браслет "Защита воина"', 'https://via.placeholder.com/300x200', 'https://t.me/IgEfR')">Заказать</a>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200" alt="Браслет 3" id="bracelet3">
                <h2>Браслет "Энергия земли"</h2>
                <p>Сила природы в каждой нити.</p>
                <p><strong>Цена: 1700 руб.</strong></p>
                <a href="#" class="button" onclick="loadImageAndOpenTelegram(event, 'Браслет "Энергия земли"', 'https://via.placeholder.com/300x200', 'https://t.me/IgEfR')">Заказать</a>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200" alt="Браслет 4" id="bracelet4">
                <h2>Браслет "Огонь души"</h2>
                <p>Талисман страсти и решимости.</p>
                <p><strong>Цена: 1600 руб.</strong></p>
                <a href="#" class="button" onclick="loadImageAndOpenTelegram(event, 'Браслет "Огонь души"', 'https://via.placeholder.com/300x200', 'https://t.me/IgEfR')">Заказать</a>
            </div>
        </div>
        <div class="order-container">
            <h3>Вы выбрали:</h3>
            <p id="orderName"></p>
            <img id="orderImage" src="" alt="Изображение браслета не выбрано" style="visibility: hidden;">
        </div>
    </div>

    <script>
        function loadImageAndOpenTelegram(event, braceletName, imageUrl, telegramLink) {
            // Останавливаем стандартное поведение ссылки (переход по странице)
            event.preventDefault();
            
            // Заменяем изображение и название в контейнере на выбранное
            document.getElementById('orderImage').src = imageUrl;
            document.getElementById('orderImage').style.visibility = 'visible';
            document.getElementById('orderName').textContent = braceletName;
            
            // Открываем ссылку на Telegram в новой вкладке
            window.open(telegramLink, '_blank');
        }
    </script>
</body>
</html>
