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
        .product img {
            width: 100%;
            border-radius: 10px;
            max-width: 600px;
            height: auto;
        }
        .button {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            background: #ff5733;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        @media (max-width: 768px) {
            .container {
                width: 90%;
                padding: 15px;
            }
            .product img {
                max-width: 100%;
            }
        }
        @media (max-width: 480px) {
            h1 {
                font-size: 1.5em;
            }
            .button {
                padding: 8px 16px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Стильные Плетеные Браслеты</h1>
        <div class="product">
            <img src="https://via.placeholder.com/600x400" alt="Браслет">
            <h2>Браслет "Сила природы"</h2>
            <p>Ручная работа, натуральные материалы, оберег.</p>
            <p><strong>Цена: 1500 руб.</strong></p>
            <a href="https://t.me/yourtelegram" class="button">Заказать в Telegram</a>
        </div>
    </div>
</body>
</html>
