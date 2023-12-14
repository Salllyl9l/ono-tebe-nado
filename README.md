<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Оно тебе надо — аукцион вещей, в которые никто не верил</title>
    <link rel="stylesheet" href="./styles/global.css"> 
    <link rel="stylesheet" href="./fonts/fonts.css">
    <link rel="stylesheet" href="./styles/style.css"> 
  </head>
  <body>
    <header class="header container">
      <nav class="header__menu">
        <ul class="header__links-list">
            <li class="header__links-list-item_no-bullit">
              <a class="header__link">главная</a>
            </li>
            <li class="header__links-list-item">
              <a class="header__link_active" href="#">посмотреть лоты</a>
            </li>
            <li class="header__links-list-item">
              <a  class="header__link_active" href="#">об аукционе</a>
            </li>
        </ul>
      </nav>
    <a class="header__logo">
      <img class="header__logo-image" src="./images/logo-black.svg" alt="Логотип">
  </a>
  <div class="header__address">
    <a href="tel:+9 999 555 5555">+9 999 555 5555 <br></a>
    <a href="mailto:info@sobaka.ge">info@sobaka.ge</a>
    <address>наб. Принсенграхт 263-265, <br>Амстердам</address>
  </div>
  </header>
  <main>
    <section class="cover">
      <div class="overlay"></div>
      <h1 class="cover__title container">
        <span class="aligned-text">
          <span>о<span class="letter-spacing-extended">но</span></span>
        </span>
        <span class="aligned-text aligned-text_center">
          <span>те</span><span class="letter-spacing-extended">бе</span>
        </span>
        <span class="aligned-text aligned-text_right">
          <span class="letter-spacing-extended">н</span><span>ад</span><span class="no-letter-spacing">о</span>
        </span>
      </h1>
      <div class="cover__description">
        <h2 class="cover__description-text">Аукцион вещей, в которые никто не верил</h2>
          <button class="bet-button">Сделать ставку</button>
      </div>
    </section>
    <section class="lots section_container">
      <h2 class="lots__heading">Лоты</h2>
      <ul class="lots__card-list">
          <article class="card card_type_film">   
          <a class="card-link" href="#">
            <div class="overlay"></div> 
          <div class="card__body">
            <h3 class="h3 card__title">
              Фильм режиссёра, который  бросил киношколу
            </h3>
            <p class="card__text">
              Не просто бросил, а ушёл с первой лекции. Какой была бы ваша 
              ставка, если бы вы не знали, что режиссёр — Пол Томас Андерсон?
            </p>
            </div>
          </div>
        </a>
        </article>
          <article class="card card_type_book">
            <a class="card-link" href="#">
            <div class="overlay"></div>
            <div class="card__body">
            <h3 class="h3 card__title">
              Книга, где описан один скучный день из жизни рекламного агента
            </h3>
          <p class="card__text">
            Объёмом почти в тысячу страниц. Иногда без знаков препинания 
            и с переходами на древнеанглийский. В ней одновременно рассказывается
            о 16 июня 1904 года и об истории литературы, начиная с античных времён. 
            И это всё накладывается на эпическую поэму Гомера. Сколько бы вы поставили 
            на «Улисса» Джеймса Джойса?
          </p>
        </div>
        </a>
        </article>
          <article class="card card_type_picture">
            <a class="card-link" href="#">
            <div class="overlay"></div> 
            <div class="card__body">
            <h3 class="card__title"> 
              Картина, которую повторит даже 5-летний сын маминой подруги
            </h3>  
          <p class="card__text">
            Ну действительно, там линия, тут кружочек, а здесь и вовсе что-то похожее 
            на инфузорию-туфельку. Никаких полей, лесов, котиков… Сколько бы вы на такое 
            поставили, если бы не знали, что это — одна из революционных работ Кандинского?
          </p>
        </div>
        </a>
        </article>
      </ul>
      <a class="lots__look-more-link" href="">посмотреть больше</a>
    </section>
    <section class="about about__container">
      <div class="about__logo">
      <img src="./images/logo-white.svg" alt="Логотип" class="about__logo-image">
      </div>
       <div class="about__column">
        <h2 class="about__title">Об аукционе</h2>
          <p class="about__text">Здесь вы не встретите очередное пафосное собрание невероятно дорогого антиквариата. Наши лоты вообще не должны были попасть ни на один аукцион. Потому что кому нужен дневник девочки-подростка или картина, которую может нарисовать даже ребёнок? Кому нужны все эти странные вещи, созданные любителями?</p>
          <p class="about__text">Слишком сложные или, наоборот, слишком простые. Опережающие своё время. В пух и прах растерзанные критиками. Непринятые и непонятые. Когда-то они казались просто неудачными. Но, несмотря на критику, кажущуюся простоту или сложность, сейчас без этих лотов невозможно представить современную культуру. Когда в эти вещи не верил никто, продолжали верить их создатели. И сейчас эти лоты стали культовыми.
        </p>
      </div>
    </section>
  </main>
  <footer class="footer">
    <div class="footer__contacts">
      <a href="tel:+9 999 555 5555">+9 999 555 5555 <br></a>
      <a href="mailto:info@sobaka.ge">info@sobaka.ge</a>
      <address>наб. Принсенграхт 263-265, <br>Амстердам</address>
    </div>
      <nav class="footer__menu">
        <ul class="footer__menu-list">
          <li class="footer__menu-list-item">главная</li>
          <li class="footer__menu-list-item ">
            <a class="footer__menu-link_active" href="#">посмотреть лоты</a>
          </li>
          <li class="footer__menu-list-item">
            <a  class="footer__menu-link" href="#">об аукционе</a>
          </li>
        </ul>
      </nav>
      <div class="footer__socials">
        <ul class="footer__social-list">
          <li class="footer__social-list-item">
            <a class="social_icon" href="#">
            <img class="footer__social-icon" src="../images/yt.svg" alt="youtube"/>
            </a>
          </li>
          <li class="footer__social-list-item">
            <a class="social_icon" href="#">
            <img class="footer__social-icon" src="../images/vk.svg" alt="vk"/>
            </a>
          </li>
          <li class="footer__social-list-item">
            <a class="social_icon" href="#">
            <img class="footer__social-icon" src="../images/pinterest.svg" alt="pinterest"/>
            </a>
          </li>
        </ul>
      </div>
    </footer>
  </body>
</html>
