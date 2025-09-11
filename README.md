<html>
<head>
  <meta charset="UTF-8">
  <title>Buffalo County Times</title>
  <style>
   nokia {
  width: 83px;
  height: 227px;
  object-fit: contain;
     }
    body {
      background-color: #1e1e1e;
      font-family: Arial, Helvetica, sans-serif;
      font-size: 14px;
      color: #e0e0e0;
      margin: 0;
      padding: 0;
    }
    table.layout {
      width: 100%;
      border: 0;
      cellspacing: 0;
      cellpadding: 0;
      height: 100vh;
    }
    td.header {
      background-color: #003366;
      color: #ffffff;
      font-size: 28px;
      font-weight: bold;
      padding: 15px;
      text-align: center;
    }
    td.menu {
      background-color: #2b2b2b;
      width: 180px;
      vertical-align: top;
      padding: 10px;
      font-size: 13px;
    }
    td.content {
      background-color: #2a2a2a;
      padding: 20px;
      vertical-align: top;
      width: 100%;
    }
    .news-title {
      font-size: 20px;
      font-weight: bold;
      color: #66aaff;
      margin-bottom: 5px;
    }
    .news-date {
      font-size: 12px;
      color: #aaaaaa;
      margin-bottom: 10px;
    }
    .news-text {
      margin-bottom: 25px;
      line-height: 1.6em;
    }
    a {
      color: #66aaff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    td.footer {
      background-color: #1a1a1a;
      font-size: 11px;
      text-align: center;
      padding: 5px;
      color: #888;
    }
    .banner {
      display: block;
      margin: 10px auto;
      border: 1px solid #444;
    }
    .counter {
      font-size: 11px;
      color: #aaa;
      text-align: center;
      margin-top: 5px;
    }
    .marquee-row {
      display: flex;
      align-items: center;
      background-color: #003366;
      color: #ffffff;
      font-size: 13px;
      padding: 5px;
    }
    .marquee-row img {
      height: 40px;
      aspect-ratio: 2.35 / 1;
      margin-right: 10px;
    }
    marquee {
      flex: 1;
    }
  </style>
</head>
<body>
  <table class="layout">
    <tr>
      <td colspan="2" class="header">Buffalo County Times — Local News</td>
    </tr>
    <tr>
      <td colspan="2">
        <div class="marquee-row">
          <marquee>Добро пожаловать на Buffalo County Times. Сегодня 10 октября 2001 года.</marquee>
        </div>
      </td>
    </tr>
    <tr>
      <td class="menu">
        <b>Разделы</b><br>
        <a href="#">Главная</a><br>
        <a href="#">Политика</a><br>
        <a href="#">Экономика</a><br>
        <a href="#">Общество</a><br>
        <a href="#">Культура</a><br>
        <a href="#">Спорт</a><br>
        <a href="#">Технологии</a><br>
        <br>
        <img src="img/nokia.jpg" alt="nokia" class="banner">
      </td>
      <td class="content">
        <img src="img/banner.webp" alt="banner" class="banner">

        <div class="news-item">
          <div class="news-title">Мэр выступил с заявлением</div>
          <div class="news-date">10 октября 2001</div>
          <div class="news-text">
            Сегодня мэр Buffalo Hill обратился к жителям округа Буффало, подчеркнув необходимость единства общества и поддержки друг друга после недавних трагических событий в стране.
          </div>
        </div>

        <div class="news-item">
          <div class="news-title">Новый медицинский центр в Buffalo Hill</div>
          <div class="news-date">9 октября 2001</div>
          <div class="news-text">
            В пригороде Буффало Хилл открылся новый медицинский центр. По словам администрации, это значительно упростит доступ к лечению для жителей округа и создаст новые рабочие места.
          </div>
        </div>

        <div class="news-item">
          <div class="news-title">Фермерский рынок вновь открылся</div>
          <div class="news-date">9 октября 2001</div>
          <div class="news-text">
            Жители округа с радостью встретили возвращение фермерского рынка. Свежие овощи, фрукты и домашняя выпечка снова доступны каждую субботу на главной площади города.
          </div>
        </div>

        <div class="news-item">
          <div class="news-title">Проблемы с транспортом</div>
          <div class="news-date">8 октября 2001</div>
          <div class="news-text">
            Автобусное сообщение между Buffalo Hill и Сиэттлом временно ограничено из-за нехватки водителей. Власти обещают восстановить расписание в течение двух недель.
          </div>
        </div>

        <div class="news-item">
          <div class="news-title">Школьная команда победила соседний округ</div>
          <div class="news-date">7 октября 2001</div>
          <div class="news-text">
            Футбольная команда старшей школы Buffalo Hill одержала победу над командой округа Риверсайд. Игра собрала сотни болельщиков, которые бурно праздновали успех.
          </div>
        </div>

        <div class="news-item">
          <div class="news-title">Культурный фестиваль в Buffalo Hill</div>
          <div class="news-date">6 октября 2001</div>
          <div class="news-text">
            В городском парке прошёл ежегодный культурный фестиваль. Музыка, танцы и кулинарные угощения из разных культур собрали жителей всех возрастов.
          </div>
        </div>

      </td>
    </tr>
    <tr>
      <td colspan="2" class="footer">
        © Buffalo County Times, 2001<br>
        <div class="counter">Вы посетитель № <span id="counter">1024</span></div>
      </td>
    </tr>
  </table>
</body>
</html>

