<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Прайс-лист массаж</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #f7e9e3, #fdfdfd);
      margin: 0;
      padding: 0;
      color: #444;
    }
    header {
      background: #a46c79;
      color: white;
      text-align: center;
      padding: 30px 20px;
      font-size: 26px;
      font-weight: bold;
      letter-spacing: 1px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.15);
    }
    .container {
      max-width: 700px;
      margin: 30px auto;
      padding: 20px;
    }
    .service {
      background: white;
      margin: 15px 0;
      padding: 18px 20px;
      border-radius: 12px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      transition: transform 0.2s, box-shadow 0.2s;
    }
    .service:hover {
      transform: translateY(-3px);
      box-shadow: 0 6px 16px rgba(0,0,0,0.12);
    }
    .name {
      font-size: 18px;
      color: #5b4a4a;
    }
    .price {
      font-weight: bold;
      font-size: 18px;
      color: #8b3a62;
    }
    footer {
      text-align: center;
      margin: 40px 0 20px;
    }
    .btn {
      display: inline-block;
      background: #25d366;
      color: white;
      padding: 12px 25px;
      border-radius: 25px;
      font-size: 16px;
      font-weight: bold;
      text-decoration: none;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
      transition: background 0.2s;
    }
    .btn:hover {
      background: #20b954;
    }
  </style>
</head>
<body>
  <header>🌸 Прайс-лист массаж 🌸</header>
  <div class="container">
    <div class="service"><span class="name">Общий массаж (1 час 40 мин)</span><span class="price">1800 руб</span></div>
    <div class="service"><span class="name">Шейно-воротниковая зона (25 мин)</span><span class="price">600 руб</span></div>
    <div class="service"><span class="name">Спина + шейно-воротник (40 мин)</span><span class="price">800 руб</span></div>
    <div class="service"><span class="name">Спина + шея + руки (60 мин)</span><span class="price">1000 руб</span></div>
    <div class="service"><span class="name">Массаж головы (20 мин)</span><span class="price">600 руб</span></div>
    <div class="service"><span class="name">Массаж ног (30 мин)</span><span class="price">800 руб</span></div>
    <div class="service"><span class="name">Массаж рук (20 мин)</span><span class="price">800 руб</span></div>
  </div>
  <footer>
    <a href="https://wa.me/79624413073" class="btn">Запись в WhatsApp 💬</a>
  </footer>
</body>
</html>
