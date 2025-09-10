<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Buffalo County Times</title>
  <style>
    body {
      background-color: #f0f0f0;
      font-family: Arial, Helvetica, sans-serif;
      font-size: 14px;
      color: #000;
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
      background-color: #cccccc;
      width: 180px;
      vertical-align: top;
      padding: 10px;
      font-size: 13px;
    }
    td.content {
      background-color: #ffffff;
      padding: 20px;
      vertical-align: top;
      width: 100%;
    }
    .news-title {
      font-size: 20px;
      font-weight: bold;
      color: #003366;
      margin-bottom: 5px;
    }
    .news-date {
      font-size: 12px;
      color: #666666;
      margin-bottom: 10px;
    }
    .news-text {
      margin-bottom: 25px;
      line-height: 1.6em;
    }
    a {
      color: #003366;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    td.footer {
      background-color: #e0e0e0;
      font-size: 11px;
      text-align: center;
      padding: 5px;
    }
    .banner {
      display: block;
      margin: 10px auto;
      border: 1px solid #999;
    }
    .counter {
      font-size: 11px;
      color: #333;
      text-align: center;
      margin-top: 5px;
    }
    marquee {
      background-color: #003366;
      color: #ffffff;
      font-size: 13px;
      padding: 3px;
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
        <marquee>Добро пожаловать на Buffalo County Times. Сегодня 10 октября 2001 года.</marquee>
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
        <img src="https://via.placeholder.com/160x600?text=Banner" alt="Реклама" class="banner">
      </td>
      <td class="content">
        <img src="https://via.placeholder.com/468x60?text=Buffalo+County+Times" alt="Баннер" class="banner">

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
