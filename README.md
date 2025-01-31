<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Фотограф</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Главная страница -->
  <header>
    <div class="hero">
      <img src="background.jpg" alt="Фоновое изображение" class="parallax">
    </div>
    <div class="intro">
      <h1>Привет! Я — Ваш Фотограф</h1>
      <p>Создаю незабываемые моменты через объектив. Мой стиль — это искусство, эмоции и стильные кадры.</p>
      <nav>
        <ul>
          <li><a href="#portfolio">Портфолио</a></li>
          <li><a href="#services">Услуги</a></li>
          <li><a href="#contacts">Контакты</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Портфолио -->
  <section id="portfolio">
    <h2>Мое Портфолио</h2>
    <div class="gallery">
      <div class="photo-category">
        <h3>Свадьбы</h3>
        <div class="photo-item">
          <img src="wedding1.jpg" alt="Свадебная фотография">
          <p>Незабываемые моменты вашего важного дня.</p>
        </div>
      </div>
      <div class="photo-category">
        <h3>Портреты</h3>
        <div class="photo-item">
          <img src="portrait1.jpg" alt="Портретная фотография">
          <p>Красота и стиль в каждом кадре.</p>
        </div>
      </div>
      <div class="photo-category">
        <h3>Пейзажи</h3>
        <div class="photo-item">
          <img src="landscape1.jpg" alt="Пейзажная фотография">
          <p>Вдохновляющие виды природы.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Услуги -->
  <section id="services">
    <h2>Мои Услуги</h2>
    <p>Я предлагаю разнообразные услуги, которые подходят для любого случая.</p>
    <ul>
      <li>Фотосессии</li>
      <li>Ретушь фотографий</li>
      <li>Печать фотографий</li>
    </ul>
    <p>Цены и пакеты: по запросу.</p>
    <form>
      <label for="service-request">Запросить услугу</label>
      <input type="text" id="service-request" name="service-request" placeholder="Введите ваш запрос">
      <button type="submit">Отправить</button>
    </form>
  </section>

  <!-- Контакты -->
  <section id="contacts">
    <h2>Контактная информация</h2>
    <p>Свяжитесь со мной для получения консультации и записи на съемку.</p>
    <p>Телефон: +7 (123) 456-78-90</p>
    <p>Email: photographer@example.com</p>
    <p>Адрес: ул. Примерная, 123, г. Москва</p>
    <form>
      <label for="message">Сообщение</label>
      <textarea id="message" name="message" placeholder="Ваше сообщение"></textarea>
      <button type="submit">Отправить</button>
    </form>
    <div id="map">
      <!-- Вставьте карту с Google Maps -->
    </div>
  </section>

  <!-- О фотографе -->
  <section id="about">
    <h2>О Фотографе</h2>
    <p>Я занимаюсь фотографией более 10 лет. Мой стиль — это смешение искусства и реальности. Я вдохновляюсь природой, людьми и их историями.</p>
    <h3>Отзывы</h3>
    <div class="testimonials">
      <p>"Великолепные фотографии, которые запечатлевают лучшие моменты нашего дня!" — Иван и Мария</p>
      <p>"Очень профессиональный подход, результат превзошел все ожидания!" — Ольга П.</p>
    </div>
  </section>

  <!-- Блог -->
  <section id="blog">
    <h2>Блог</h2>
    <article>
      <h3>Как выбрать фотографа для свадьбы</h3>
      <p>Пара советов для выбора идеального фотографа...</p>
    </article>
  </section>
</body>
</html>
