<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Одностраничный сайт</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            background: #333;
            color: white;
            display: flex;
            justify-content: center;
            padding: 0.5rem;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 2rem;
            text-align: center;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
        .btn {
            background: #4CAF50;
            color: white;
            padding: 0.7rem 1.5rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .btn:hover {
            background: #45a049;
        }
    </style>
</head>
<body>

<header>
    <h1>Добро пожаловать!</h1>
    <p>Ваш одностраничный сайт с минималистичным дизайном</p>
</header>

<nav>
    <a href="#about">О нас</a>
    <a href="#services">Услуги</a>
    <a href="#contact">Контакты</a>
</nav>

<section id="about">
    <h2>О нас</h2>
    <p>Мы предоставляем лучшие услуги для наших клиентов, ориентируясь на качество и удобство.</p>
</section>

<section id="services">
    <h2>Наши услуги</h2>
    <ul>
        <li>Консультации</li>
        <li>Разработка сайтов</li>
        <li>Маркетинговые стратегии</li>
    </ul>
</section>

<section id="contact">
    <h2>Свяжитесь с нами</h2>
    <p>Email: info@example.com</p>
    <p>Телефон: +380 123 456 789</p>
    <button class="btn">Написать нам</button>
</section>

<footer>
    <p>&copy; 2025 Ваш сайт. Все права защищены.</p>
</footer>

</body>
</html>