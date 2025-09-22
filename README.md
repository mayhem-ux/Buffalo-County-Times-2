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
      }
      .news-text p {
  margin: 0 0 10px 0;   /* расстояние между репликами */
  text-indent: 20px;    /* красная строка / отступ */
    }
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
        Добро пожаловать на Buffalo County Times. Сегодня 14 октября 2001 года.
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
          <marquee>Добро пожаловать на Buffalo County Times. Сегодня 11 октября 2001 года.</marquee>
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
    <p><b>Температура:</b> +12°C</p>
    <p><b>Облачность:</b> Пасмурно</p>
    <p><b>Осадки:</b> 0 мм</p>
    </div>
    <img src="img/rek1.jpg" alt="Реклама" class="rek1">
    <img src="img/rek2.jpg" alt="Реклама" class="rek2">
      </td>
      <!-- Новости -->
      <td class="content">
        <!-- Шаблон новости (1 из 7) -->
        <div class="news-item">
          <div class="news-title">Дело закрыто!</div>
          <div class="news-date">11 октября 2001</div>
          <div class="news-text">
            Полицейское расследование в отношении бывшего окружного прокурора Буффало, Чарльза Харрингтона подошло к концу и ему окончательно предъявлены обвинения в коррупции и злоупотреблении полномочиями. В ближайшее время Харрингтона перевезут в соседний округ где начнутся судебные слушания. Наше агентство обратилось за комментарием к заместителю шерифа, однако он отметил что пока не может давать никаких пояснений по данному делу. Для жителей города это событие стало окончательной точкой в истории старого прокурора.
          </div>
          <img src="img/zad.png" alt="Фото новости" class="news-image">
        </div>

        <!-- Повтори ещё 6 таких блоков -->
        <div class="news-item">
          <div class="news-title">Дожди</div>
          <div class="news-date">11 октября 2001</div>
          <div class="news-text">
            В Буффало Хилл синоптики отмечают возвращение обильных дождей которых город не видел на протяжении долгого времени. 10 октября жители стали свидетелями сразу двух сильных ливней: первый прошел утром и слегка затопил несколько улиц в центральной части, а ближе к ночи весь город оказался под плотной стеной дождя. По прогнозам метеорологов осадки сохранятся и в ближайшие дни что может повлечь перебои в движении транспорта и локальные подтопления в низинах.
          </div>
          <img src="img/pot.png" alt="Фото новости" class="news-image">
        </div>

        <div class="news-item">
          <div class="news-title">Ярморка!</div>
          <div class="news-date">13 октября 2001</div>
          <div class="news-text">
            Сегодня в Буффало Хилл прошла очередная ярморка на этот раз посвещенная хэллуинском празднику который вот-вот наступит. Проходила она в центре города и каждый желающий мог без каикх-либо проблем ее посетить, там же граждане могли купить себе костюмы и сувениры посвещенные жуткой тематике. К слову во время мероприятия произошло действительно кое-что жуткое, очевидцы рассказывают про драку двух людей в костюмах Джейсона Вурхиза, наша редакция надеятся на то что она состоялась на кулаках, а не на мачете. Так или иначе многие довольно лестно высказываются о прошедшем мероприятии, многие закупили красивы костюмы и сувениры которые теперь пробудут с ними до следующей такой-же мимолетной ярморки. Кроме этого нашей редакции удалось взять небольшое не многословное интервью по поводу проведения мероприятия, молодые люди кроме того так-же заявили о том что у них есть собственная музыкальная группа, а заняться ярморкой они решили из собственного желания, вот что нам удалось узнать на интерьвью: 
             <p>- Вам понравилась ярморка?</p>
             <p>- Конечно-же, это одна из многочисленных ярморок в Буффало Хиллс и для нас большая честь что именно мы смогли провести ее!</p>
             <p>- Сложно ли было организовать ярморку?</p>
             <p>- Знаете на самом деле достаточно тяжело, мы получили минимальное финансирование от мэрии из-за чего многое пришлось брать из своего кармана!</p>
             <p>- А можете ли вы дать какой-нибудь коментарий по поводу произошедшей драки?</p>
             <p>- Конечно, лично мой знакомый в ней участвовал и к сожалению он проиграл! К слову хотите послушать про нашу группу...</p>
    Думаю на этом можно заканчивать статью, конечно-же нашу редакцию напрягает тот факт что на ярморке вот так просто может произойти какая-то драка, кто знает что могло бы случиться если-бы у кого-то из участников оказлся бы нож. Поэтому наша редакция настоятельно вас просит быть осторожными на подобных мероприятиях, ведь кто знает что может произойти!
          </div>
          <img src="img/hal.png" alt="Фото новости" class="news-image">
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
