<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Оно тебе надо</title>
  <link rel="stylesheet" href="../fonts/fonts.css">
  <link rel="stylesheet" href="styles/global.css">
  <link rel="stylesheet" href="styles/main.css">
</head>
<body>
  <header class="header">
    <nav class="header__menu">
      <ul class="header__links-list">
        <li class="header__links-list-item"><a href="#" class="header__link">Главная</a></li>
        <li class="header__links-list-item"><a href="#" class="header__link">Лоты</a></li>
        <li class="header__links-list-item"><a href="#" class="header__link">О проекте</a></li>
      </ul>
    </nav>
    <a href="#" class="header__logo">
      <img src="../images/logo.png" alt="Логотип «Оно тебе надо»" class="header__logo-image">
    </a>
    <address class="address header__address">
      <p>г. Москва, ул. Примерная, д. 1</p>
      <a href="tel:+74951234567" class="address__phone">+7 (495) 123-45-67</a>
      <a href="mailto:info@iteverything.ru" class="address__email">info@iteverything.ru</a>
    </address>
  </header>

  <main>
    <section class="cover">
      <div class="overlay"></div>
      <h1 class="cover__title">
        <span class="letter-spacing-extended">О</span>
        <span class="letter-spacing-extended">н</span>
        <span class="letter-spacing-extended">о</span>
        <span class="no-letter-spacing"> </span>
        <span class="letter-spacing-extended">т</span>
        <span class="letter-spacing-extended">е</span>
        <span class="letter-spacing-extended">б</span>
        <span class="letter-spacing-extended">е</span>
        <span class="no-letter-spacing"> </span>
        <span class="letter-spacing-extended">н</span>
        <span class="letter-spacing-extended">а</span>
        <span class="letter-spacing-extended">д</span>
        <span class="letter-spacing-extended">о</span>
      </h1>
      <div class="cover__description">
        <p class="cover__description-text">Аукцион вещей, в которые никто не верил</p>
        <button class="bet-button">Сделать ставку</button>
      </div>
    </section>

    <section class="lots">
      <h2 class="lots__heading">Актуальные лоты</h2>
      <ul class="lots__card-list">
        <li class="lots__card-list-item">
          <a href="#" class="card-link">
            <article class="card card_type_film">
              <div class="overlay"></div>
              <h3 class="card__title">Старый кинопроектор</h3>
              <p class="card__text">1950‑е годы, в рабочем состоянии</p>
            </article>
          </a>
        </li>
        <li class="lots__card-list-item">
          <a href="#" class="card-link">
            <article class="card card_type_book">
              <div class="overlay"></div>
              <h3 class="card__title">Редкое издание «Мастера и Маргариты»</h3>
              <p class="card__text">1967 год, тираж 5 000 экз.</p>
            </article>
          </a>
        </li>
        <li class="lots__card-list-item">
          <a href="#" class="card-link">
            <article class="card card_type_picture">
              <div class="overlay"></div>
              <h3 class="card__title">Картина неизвестного художника</h3>
              <p class="card__text">Масло, холст, 50×60 см</p>
            </article>
          </a>
        </li>
      </ul>
      <a href="#" class="lots__look-more-link">Посмотреть больше лотов</a>
    </section>

    <section class="about">
      <div class="about__column">
        <div class="about__logo">
          <img src="../images/logo-small.png" alt="Логотип" class="about__logo-image">
        </div>
      </div>
      <div class="about__column">
        <h2 class="about__title">Об аукционе</h2>
        <div class="about__text">
          <p>Наш аукцион — это место, где находят вторую жизнь вещи, которые казались никому не нужными. Мы верим, что у каждой находки есть своя история и свой покупатель.</p>
          <p>С 2020 года мы провели более 100 торгов и помогли обрести дом сотням необычных предметов.</p>
        </div>
      </div>
    </section>
  </main>

  <footer class="footer">
    <address class="address">
      <p>г. Москва, ул. Примерная, д. 1</p>
      <a href="tel:+74951234567" class="address__phone">+7 (495) 123-45-67</a>
      <a href="mailto:info@iteverything.ru" class="address__email">info@iteverything.ru</a>
    </address>
    <nav class="footer__menu">
      <ul class="footer__menu-list">
        <li class="footer__menu-list-item"><a href="#" class="footer__menu-link">Главная</a></li>
        <li class="footer__menu-list-item"><a href="#" class="footer__menu-link">Лоты</a></li>
        <li class="footer__menu-list-item"><a href="#" class="footer__menu-link">О проекте</a></li>
        <li class="footer__menu-list-item"><a href="#" class="footer__menu-link">Контакты</a></li>
      </ul>
    </nav>
    <ul class="footer__social-list">
      <li class="footer__social-list-item">
        <a href="#" class="footer__social-link">
          <img src="../images/social-vk.png" alt="VK" class="footer__social-icon">
        </a>
      </li>
      <li class="footer__social-list-item">
        <a href="#" class="footer__social-link">
          <img src="../images/social-tg.png" alt="Telegram" class="footer__social-icon">
        </a>
      </li>
      <li class="footer__social-list-item">
        <a href="#" class="footer__social-link">
          <img src="../images/social-yt.png" alt="YouTube" class="footer__social-icon">
        </a>
      </li>
    </ul>
  </footer>
</body>
</html>
