<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой Discord сайт</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #2c2f33, #23272a);
            color: white;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            text-align: center;
            padding: 30px;
        }

        h1 {
            margin-bottom: 10px;
        }

        .card {
            background: #1e2124;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.5);
            margin: 20px;
            text-align: center;
        }

        img {
            width: 100%;
            max-width: 300px;
            border-radius: 10px;
            margin-top: 10px;
        }

        iframe {
            border-radius: 10px;
        }

        button {
            margin-top: 15px;
            padding: 10px 20px;
            border: none;
            border-radius: 8px;
            background: #7289da;
            color: white;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background: #5b6eae;
        }

        footer {
            margin-top: 30px;
            opacity: 0.6;
            font-size: 14px;
            padding-bottom: 20px;
        }
    </style>
</head>

<body>

<header>
    <h1>Добро пожаловать на сайт</h1>
    <p>Подключайся к нашему Discord серверу</p>
</header>

<div class="card">
    <h2>Картинка (пример)</h2>
    <img src="https://via.placeholder.com/300" alt="Пример картинки">
</div>

<div class="card">
    <h2>Discord</h2>
    <iframe 
        src="https://discord.com/widget?id=1488223934120857700&theme=dark"
        width="350"
        height="500"
        allowtransparency="true"
        frameborder="0"
        sandbox="allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts">
    </iframe>
</div>

<div class="card">
    <button onclick="alert('Кнопка работает!')">Нажми меня</button>
</div>

<footer>
    © 2026 Мой сайт
</footer>

</body>
</html>
