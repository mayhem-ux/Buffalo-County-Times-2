<html>
<head>
  <meta charset="UTF-8">
  <title>Buffalo County Times</title>
  <style>
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
      width: 250px;
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
      margin-bottom: 15px;
      line-height: 1.6em;
    }
    .news-image {
      width: 100%;
      max-width: 1920px;
      height: auto;
      border: 1px solid #444;
      margin-bottom: 30px;
      display: block;
    }
    .banner {
      display: block;
      margin: 15px auto;
      max-width: 1024px;
      height: auto;
      border: 1px solid #444;
    }
    .ad {
      display: block;
      margin: 20px auto;
      width: 100%;
      max-width: 736px;
      height: auto;
      border: 1px solid #444;
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
    .counter {
      font-size: 11px;
      color: #aaa;
      text-align: center;
      margin-top: 5px;
     .rek1 {
     display: block;
      margin: 20px auto;
      width: 100%;
      max-width: 736px;
      height: auto;
      border: 1px solid #444;
    .rek2 {
     display: block;
      margin: 20px auto;
      width: 100%;
      max-width: 736px;
      height: auto;
      border: 1px solid #444;
    }
    }
    <!-- Бегущая строка -->
<tr>
  <td colspan="2">
    <div class="marquee-row">
      <marquee>
        Добро пожаловать на Buffalo County Times. Сегодня 10 октября 2001 года.
      </marquee>
    </div>
  </td>
</tr>
    }
.marquee-row {
  display: flex;
  align-items: center;
  background-color: #ffffff; /* белый фон под бегущей строкой */
  font-size: 13px;
  padding: 5px;
  border: 1px solid #ccc;   /* тонкая рамка по желанию */
}
.marquee-row img {
  height: 40px;
  aspect-ratio: 2.35 / 1;
  margin-right: 10px;
}
marquee {
  flex: 1;
  color: #000000;       /* текст чёрный */
  font-weight: bold;    /* жирный */
}
}
    .weather {
  margin-top: 20px;
  padding: 15px;
  background-color: #1f1f1f;
  border: 1px solid #444;
  text-align: left;
  font-size: 16px;
  line-height: 1.6em;
}
}
.weather h4 {
  margin: 0 0 10px 0;
  color: #66aaff;
}
}
  </style>
</head>
<body>
  <table class="layout">
    <!-- Заголовок -->
    <tr>
      <td colspan="2" class="header">Buffalo County Times — Local News</td>
    </tr>

    <!-- Бегущая строка + баннер -->
    <tr>
      <td colspan="2">
        <div class="marquee-row">
          <marquee>Добро пожаловать на Buffalo County Times. Сегодня 10 октября 2001 года.</marquee>
        </div>
        <img src="img/banner.webp" alt="banner" class="banner">
      </td>
    </tr>

    <!-- Основная часть -->
    <tr>
      <!-- Меню -->
      <td class="menu">
        <b>Разделы</b><br>
        <a href="#">Главная</a><br>
        <a href="#">Политика</a><br>
        <a href="#">Экономика</a><br>
        <a href="#">Общество</a><br>
        <a href="#">Культура</a><br>
        <a href="#">Спорт</a><br>
        <a href="#">Технологии</a><br>

        <!-- Блок рекламы -->
        <img src="img/nokia.jpg" alt="Реклама" class="ad">

        <!-- Погода -->
      <div class="weather">
    <h4>Погода в Buffalo Hill</h4>
    <p><b>Температура:</b> +13°C</p>
    <p><b>Облачность:</b> Переменная</p>
    <p><b>Осадки:</b> 0 мм</p>
    </div>
    <img src="img/rek1.jpg" alt="Реклама" class="rek1">
    <img src="img/rek2.jpg" alt="Реклама" class="rek2">
      </td>
      <!-- Новости -->
      <td class="content">
        <!-- Шаблон новости (1 из 7) -->
        <div class="news-item">
          <div class="news-title">Памятный митинг</div>
          <div class="news-date">10 октября 2001</div>
          <div class="news-text">
            В пригороде Сиэттла прошел памятный митинг в честь жертв терактов 11 сентября - власти сообщили об опознании еще трех жителей штата, погибших в башнях-близнецах.
          </div>
          <img src="img/sept.jpg" alt="Фото новости" class="news-image">
        </div>

        <!-- Повтори ещё 6 таких блоков -->
        <div class="news-item">
          <div class="news-title">Ремонт дороги</div>
          <div class="news-date">8 октября 2001</div>
          <div class="news-text">
            В центре Буффало Хилл начались работы по ремонту дорожного покрытия: движение на пересечении Пайн-стрит и Мейн-стрит будет ограничено на два дня.
          </div>
          <img src="img/rem.jpg" alt="Фото новости" class="news-image">
        </div>

        <div class="news-item">
          <div class="news-title">Благотворительный концерт</div>
          <div class="news-date">8 октября 2001</div>
          <div class="news-text">
            В местной школе прошел благотворительный концерт - собранные средства направят в фонд помощи пострадавшим в Нью-Йорке.
          </div>
          <img src="img/Concert.jpg" alt="Фото новости" class="news-image">
        </div>

        <div class="news-item">
          <div class="news-title">Проблемы с транспортом</div>
          <div class="news-date">8 октября 2001</div>
          <div class="news-text">
            Автобусное сообщение между Буффало Хиллс и Сиэттлом временно ограничено из-за нехватки водителей. Власти обещают восстановить расписание в течение недели.
          </div>
          <img src="img/avtob.jpg" alt="Фото новости" class="news-image">
        </div>

        <div class="news-item">
          <div class="news-title">Заморозки</div>
          <div class="news-date">7 октября 2001</div>
          <div class="news-text">
            На прошлой неделе зафиксирован первый заморозок: фермеры округа предупреждают о возможной потере части урожая.
          </div>
          <img src="img/zam.jpg" alt="Фото новости" class="news-image">
        </div>

        <div class="news-item">
          <div class="news-title">Отмененный фестиваль</div>
          <div class="news-date">6 октября 2001</div>
          <div class="news-text">
           Городской фестиваль был отменен, из-за этических соображений и сочуствий в связи с трагедией 11-го числа, а так-же из-за соображения безопастности.
          </div>
          <img src="img/fes.jpg" alt="Фото новости" class="news-image">
        </div>

        <div class="news-item">
          <div class="news-title">Скандальный арест окружного прокурора</div>
          <div class="news-date">6 октября 2001</div>
          <div class="news-text">
            На днях федеральные агенты ФБР произвели арест окружного прокурора округа Буффало Чарльза Харрингтона. Ему предъявлены обвинения в получении взяток в особо крупных размерах.

           По сведениям источников, на протяжении последних лет своей деятельности Харрингтон систематически занимался фальсификацией и уничтожением вещественных доказательств за денежные вознаграждения, что позволило избежать наказания ряду опасных преступников.

          Временно исполняющим обязанности назначен его единственный помощник. Новые выборы окружного прокурора округа Буффало состоятся в ближайшие месяцы.
          </div>
          <img src="img/arest.jpg" alt="Фото новости" class="news-image">
        </div>
      </td>
    </tr>

    <!-- Подвал -->
    <tr>
      <td colspan="2" class="footer">
        © Buffalo County Times, 2001<br>
        <div class="counter">Вы посетитель № <span id="counter">6026</span></div>
      </td>
    </tr>
  </table>
</body>
</html>
