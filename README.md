<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Психологический центр «Гармония»</title>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        color: #333;
        background: #f7f9fb;
    }

    header {
        background: #6fa8dc;
        color: white;
        text-align: center;
        padding: 60px 20px;
    }

    header h1 {
        font-size: 2.5rem;
        margin-bottom: 10px;
    }

    section {
        max-width: 1000px;
        margin: 40px auto;
        padding: 0 20px;
    }

    .services {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 20px;
    }

    .card {
        background: white;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .card h3 {
        color: #4a86c5;
        margin-bottom: 10px;
    }

    .contacts {
        background: white;
        padding: 30px;
        border-radius: 10px;
        text-align: center;
    }

    .btn {
        display: inline-block;
        margin-top: 15px;
        padding: 12px 25px;
        background: #4a86c5;
        color: white;
        text-decoration: none;
        border-radius: 5px;
    }

    .btn:hover {
        background: #376ca3;
    }

    footer {
        text-align: center;
        padding: 20px;
        background: #e8eef5;
        margin-top: 40px;
    }
</style>
</head>

<body>

<header>
    <h1>Психологический центр «Гармония»</h1>
    <p>Профессиональная психологическая помощь для взрослых, детей и семей</p>
</header>

<section>
    <h2>О нас</h2>
    <p>
        Мы помогаем людям справляться со стрессом, тревогой,
        жизненными кризисами и сложностями в отношениях.
        Наши специалисты используют современные и доказательные
        методы психологического консультирования.
    </p>
</section>

<section>
    <h2>Наши услуги</h2>

    <div class="services">
        <div class="card">
            <h3>Индивидуальная консультация</h3>
            <p>Поддержка в решении личных и эмоциональных вопросов.</p>
        </div>

        <div class="card">
            <h3>Семейная терапия</h3>
            <p>Помощь в улучшении отношений между близкими людьми.</p>
        </div>

        <div class="card">
            <h3>Детский психолог</h3>
            <p>Работа с эмоциональными и поведенческими трудностями детей.</p>
        </div>

        <div class="card">
            <h3>Онлайн-консультации</h3>
            <p>Удобный формат встреч из любой точки мира.</p>
        </div>
    </div>
</section>

<section>
    <h2>Почему выбирают нас</h2>
    <ul>
        <li>✔ Опытные специалисты</li>
        <li>✔ Конфиденциальность</li>
        <li>✔ Индивидуальный подход</li>
        <li>✔ Очный и онлайн формат</li>
    </ul>
</section>

<section>
    <div class="contacts">
        <h2>Записаться на консультацию</h2>
        <p>Телефон: +7 (999) 123-45-67</p>
        <p>Email: info@harmony-center.ru</p>
        <p>Адрес: г. Москва, ул. Примерная, д. 10</p>

        <a href="tel:+79991234567" class="btn">
            Позвонить
        </a>
    </div>
</section>

<footer>
    <p>© 2026 Психологический центр «Гармония». Все права защищены.</p>
</footer>

</body>
</html>
