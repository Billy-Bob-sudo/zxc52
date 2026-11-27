[index.html](https://github.com/user-attachments/files/35509089/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/modal.css">
</head>
<body>
<div class="container">
    <header class="header">
    <div class="header__logo">
        <img src="img/sign.png" alt="logo">
        <p class="header__logo-name">Видеосервис</p>
    </div>
    <form class="header__search">
        <input class="header__search-txt" placeholder="Поиск..." type="text">
        <input type="button" class="search-button" value="Найти">
    </form>
    <nav class="header__login">
        <input type="button" class="login-button" popovertarget="modal" value="Войти">
    </nav>
</header>
    <main>
        <div class="type-choose">
            <a href="index.html" class="type-choose__ref type-choose__current">Фильмы</a>
            <a href="channels.html" class="type-choose__ref">Телеканалы</a>
        </div>
            <p class="news__title">🔥Новинки</p>
        <div class="news">
        <div>
            <img src="img/cat.svg" alt="cat picture" class="news__img">
            <p class="news__desc">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <p class="news__txt">Мульт в кино. Выпуск №103. Некогда грустить!</p>
        </div>
        <div>
            <img src="img/batman.svg" alt="batman picture" class="news__img">
            <p class="news__desc">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <p class="news__txt">Новый Бэтмен</p>
        </div>
        <div>
            <img src="img/hollywood.svg" alt="hollywood-picture" class="news__img">
            <p class="news__desc">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <p class="news__txt">Однажды... в Голливуде</p>
        </div>
        <div>
            <img src="img/strp.svg" alt="girl-picture" class="news__img">
            <p class="news__desc">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <p class="news__txt">Стриптизёрши</p>
        </div>    
        </div>
        <p class="genres__title">Жанры</p>
    <ul class="genres__list">
    <li class="genre genre--comedy">
      <div class="genre__emoji">😁</div>
      <div class="genre__name">Комедии</div>
    </li>
    <li class="genre genre--drama">
      <div class="genre__emoji">😭</div>
      <div class="genre__name">Драмы</div>
    </li>
    <li class="genre genre--fantasy">
      <div class="genre__emoji">👽</div>
      <div class="genre__name">Фантастика</div>
    </li>
    <li class="genre genre--horror">
      <div class="genre__emoji">👻</div>
      <div class="genre__name">Ужасы</div>
    </li>
  </ul>
    </main>
</div>
    <footer class="footer">
    <div class="container footer__inner">
        <img src="img/Footer-logo.svg" alt="logo" class="footer__logo">
        <div class="footer__info">
            <p>426057, Россия, Удмуртская Республика, г. Ижевск, ул. Карла Маркса, 246 (ДК «Металлург»)</p>
            <p style="margin-top: 6px;">+7 (3412) 93-88-61, 43-29-29</p>
            <p class="footer__txt-web" style="font-weight: bold;">htc-cs.ru</p>
        </div>
    </div>
</footer>

<div class="modal" id="modal" popover>
    <h1 class="modal__title">Вход</h1>
    <form class="modal__form">
        <input class="modal__txt-input" placeholder="Логин" type="text">
        <input class="modal__txt-input" placeholder="Пароль" type="password">
        <div class="modal__remember">
            <input type="checkbox" id="check1" class="modal__check">
            <label for="check1" class="modal__label">
                <span class="checkmark">&#10004;</span>
                Запомнить
            </label>
        </div>
        <input type="button" class="login-button modal__submit" value="Войти">
    </form>
</div>
</body>
</html>
