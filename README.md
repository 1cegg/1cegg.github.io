<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Группировка Долг</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: url('https://example.com/your-background-image.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #fff;
        }
        header {
            background-color: rgba(0, 0, 0, 0.7);
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
            font-size: 3em;
            color: #ff0000; /* Красный цвет для заголовка */
        }
        .sidebar {
            position: fixed;
            left: 0;
            top: 100px;
            width: 200px;
            background-color: rgba(0, 0, 0, 0.8);
            padding: 15px;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);
        }
        .sidebar a {
            display: block;
            color: #fff;
            text-decoration: none;
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .sidebar a:hover {
            background-color: #ff0000; /* Красный цвет при наведении */
        }
        .content {
            margin-left: 220px; /* Отступ для бокового меню */
            padding: 20px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: rgba(0, 0, 0, 0.7);
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .button {
            background-color: #ff0000; /* Красная кнопка */
            border: none;
            color: white;
            padding: 15px 30px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 4px 2px;
            cursor: pointer;
            border-radius: 5px;
        }
        .button:hover {
            background-color: #cc0000; /* Темнее при наведении */
        }
    </style>
</head>
<body>

<header>
    <h1>Группировка Долг</h1>
</header>

<div class="sidebar">
    <h2>Меню</h2>
    <a href="#mission">Миссии</a>
    <a href="#equipment">Экипировка</a>
    <a href="#members">Члены</a>
    <a href="#reports">Отчеты</a>
    <a href="#contacts">Контакты</a>
</div>

<div class="content">
    <section id="mission">
        <h2>Миссии</h2>
        <p>Здесь будут описаны ваши текущие миссии.</p>
        <button class="button">Начать новую миссию</button>
    </section>

    <section id="equipment">
        <h2>Экипировка</h2>
        <p>Посмотрите доступную экипировку.</p>
    </section>

    <section id="members">
        <h2>Члены группировки</h2>
        <p>Информация о членах группировки.</p>
    </section>

    <section id="reports">
        <h2>Отчеты</h2>
        <p>Просмотр отчетов о выполненных миссиях.</p>
    </section>

    <section id="contacts">
        <h2>Контакты</h2>
        <p>Контактная информация для связи.</p>
    </section>
</div>

<footer>
    <p>&copy; 2023 Группировка Долг. Все права защищены.</p>
</footer>

</body>
</html>
