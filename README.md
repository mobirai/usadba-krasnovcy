<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Усадьба в Красновцах</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>

    <!-- Навигация -->
    <header>
        <h1>Усадьба в Красновцах</h1>
        <nav>
            <a href="#weddings">Свадьбы</a>
            <a href="#birthdays">Дни рождения</a>
            <a href="#corporates">Корпоративы</a>
            <a href="#gallery">Галерея</a>
            <a href="#contact">Контакты</a>
        </nav>
    </header>

    <!-- Раздел: Свадьбы -->
    <section id="weddings">
        <h2>Свадьбы</h2>
        <p>Идеальное место для проведения незабываемых свадебных церемоний.</p>
        <img src="https://via.placeholder.com/800x400" alt="Свадебное оформление">
    </section>

    <!-- Раздел: Дни рождения -->
    <section id="birthdays">
        <h2>Дни рождения</h2>
        <p>Празднуйте день рождения в уютной атмосфере с вкусной кухней и развлечениями.</p>
        <img src="https://via.placeholder.com/800x400" alt="Празднование дня рождения">
    </section>

    <!-- Раздел: Корпоративы -->
    <section id="corporates">
        <h2>Корпоративы</h2>
        <p>Организуйте корпоративное мероприятие в красивом месте с природой и уютом.</p>
        <img src="https://via.placeholder.com/800x400" alt="Корпоративное мероприятие">
    </section>

    <!-- Галерея -->
    <section id="gallery">
        <h2>Галерея</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/300x200" alt="Фото 1">
            <img src="https://via.placeholder.com/300x200" alt="Фото 2">
            <img src="https://via.placeholder.com/300x200" alt="Фото 3">
        </div>
    </section>

    <!-- Контакты -->
    <section id="contact">
        <h2>Контакты</h2>
        <p>📍 Усадьба в деревне Красновцы, Лидский район, ул. Шоссейная 4а</p>
        <p>📞 Телефон: +375 29 2677777</p>

        <h3>Форма обратной связи</h3>
        <form>
            <input type="text" name="name" placeholder="Ваше имя" required>
            <input type="email" name="email" placeholder="Ваш email" required>
            <textarea name="message" placeholder="Ваше сообщение" required></textarea>
            <button type="submit">Отправить</button>
        </form>

        <h3>Карта</h3>
        <div id="map"></div>
    </section>

    <footer>
        <p>© 2024 Усадьба в Красновцах. Все права защищены.</p>
    </footer>

</body>
</html>
