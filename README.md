<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Мой Стриминг</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f7f7f7;
      color: #333;
    }
    header, footer {
      background-color: #ffffff;
      padding: 20px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #007acc;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      color: #007acc;
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
    }
    form button {
      padding: 10px 20px;
      background-color: #007acc;
      color: white;
      border: none;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>Мой Стриминг</h1>
    <nav>
      <a href="#about">Обо мне</a>
      <a href="#matches">Ближайшие матчи</a>
      <a href="#order">Заказать стрим</a>
      <a href="#faq">Вопрос-ответ</a>
      <a href="#contact">Контакты</a>
    </nav>
  </header>

  <section id="about">
    <h2>Обо мне</h2>
    <p>Привет! Я стример STANDOFF 2, участвую в турнирах и провожу прямые эфиры. Подключайся и следи за матчами в реальном времени!</p>
  </section>

  <section id="matches">
    <h2>Ближайшие матчи</h2>
    <ul>
      <li>Team Xurse vs Figments — 18 мая, 19:00</li>
      <li>Stream Party — 20 мая, 21:00</li>
    </ul>
  </section>

  <section id="order">
    <h2>Заказать стрим</h2>
    <form>
      <input type="text" placeholder="Ваше имя" required />
      <input type="email" placeholder="Email для связи" required />
      <textarea rows="4" placeholder="Что стримить?"></textarea>
      <button type="submit">Отправить запрос</button>
    </form>
  </section>

  <section id="faq">
    <h2>Вопрос-ответ</h2>
    <p><strong>Как часто проходят стримы?</strong><br>Обычно 2–3 раза в неделю.</p>
    <p><strong>Можно ли заказать совместный стрим?</strong><br>Да, напишите в форме выше.</p>
  </section>

  <section id="contact">
    <h2>Контакты</h2>
    <p>Email: yourname@example.com</p>
    <p>VK: <a href="https://vk.com/yourpage" target="_blank">vk.com/yourpage</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Мой Стриминг</p>
  </footer>
</body>
</html>
