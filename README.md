<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мій інтернет-магазин</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            background-color: #f7f7f0;
            font-family: Arial, sans-serif;
        }
        h1, h2, h3, h4 {
            color: #333;
        }
        p {
            line-height: 1.5;
            color: #666;
        }
        hr {
            border: 1px solid #cccccc;
            margin: 20px 0;
        }
        ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }
        li {
            margin: 10px 0;
        }
        img {
            vertical-align: middle;
            margin-right: 10px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        table, th, td {
            border: 1px solid #ccc;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        button[type="reset"] {
            background-color: #f44336;
        }
        button:hover {
            opacity: 0.8;
        }
        input, textarea, select {
            padding: 8px;
            width: 100%;
            box-sizing: border-box;
            margin-bottom: 10px;
        }
        iframe {
            max-width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://assets.onecompiler.app/437k7t89t/437k6wca9/%D0%91%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20(2).jpg" alt="Логотип магазину" width="100" height="100">
        <h1>Мій магазин спортивного одягу</h1>
    </header>

    <section>
        <h2>Категорії товарів</h2>
        <ul>
            <li>Спортивні костюми</li>
            <li>Кросівки</li>
            <li>Аксесуари</li>
        </ul>
    </section>

    <section>
        <h2>Як зробити замовлення</h2>
        <ol>
            <li>Обрати категорію та знайти товар</li>
            <li>Додати товар у кошик</li>
            <li>Оплатити товар</li>
        </ol>
    </section>

    <section>
        <h2><strong>Знижки</strong></h2>
        <h3>Пропозиції</h3>
        <h4>Товари</h4>

        <h2>Ціна</h2>
        <table>
            <tr>
                <th>Товар</th>
                <th>Ціна</th>
                <th>Наявність</th>
            </tr>
            <tr>
                <td>Спортивний костюм</td>
                <td>13 000 грн</td>
                <td>Є в наявності</td>
            </tr>
            <tr>
                <td>Кросівки</td>
                <td>6 500 грн</td>
                <td>Є в наявності</td>
            </tr>
        </table>

        <a href="https://youtu.be/NYSLJd-_wHs?si=pzlmBsYKAm7QjYU6">Відео-огляд товарів</a>
    </section>

    <section>
        <h2>Відеоогляд нашого товару</h2>
        <iframe width="560" height="315" src="https://youtu.be/oZoX3TgMzDI?si=WCi2YvTg0PB3a9JC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </section>

    <section>
        <h2>Зв'язатися з нами</h2>
        <p>Більше інформації дивіться на нашій офіційній сторінці:</p>
        <a href="https://youtu.be/hvL1339luv0?si=gKAHB0pYhYmkL3XC">Офіційний сайт магазину</a>
    </section>

    <section>
        <h2>Наше розташування</h2>
        <iframe src="https://www.google.com/maps/embed?pb=..." width="450" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </section>

    <section>
        <h2>Залишити відгук</h2>
        <form action="#" method="POST">
            <p>
                <label for="name">Ім'я:</label>
                <input type="text" id="name" name="name" required minlength="2">
            </p>
            <p>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </p>
            <p>
                <label for="rating">Оцініть якість товару:</label>
                <select id="rating" name="rating">
                    <option value="5">5 - Чудово</option>
                    <option value="4">4 - Добре</option>
                    <option value="3">3 - Задовільно</option>
                    <option value="2">2 - Погано</option>
                    <option value="1">1 - Ти шо? Це жахіття</option>
                </select>
            </p>
            <p>
                <label for="review">Ваш відгук:</label>
                <textarea id="review" name="review" rows="4" cols="50" required></textarea>
            </p>
            <button type="reset">Очистити</button>
            <button type="submit">Надіслати</button>
        </form>
    </section>

    <footer>
        <p>© 2025 Мій інтернет-магазин. Всі права захищені.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
