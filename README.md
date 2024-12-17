<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GameSell - Магазин видеоигр</title>
    <link rel="stylesheet" href="GameSell2.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <!-- Шапка -->
    <header>
        <div class="container">
            <h1>GameSell</h1>
            <nav>
                <ul>
                    <li><a href="#popular-games">Популярные игры</a></li>
                    <li><a href="#new-releases">Новинки</a></li>
                    <li><a href="#sales">Акции</a></li>
                    <li><a href="#about-us">О нас</a></li>
                </ul>
            </nav>
            <div class="cart">
                <i class="fas fa-shopping-cart" id="cart-icon"></i>
                <span id="cart-count">0</span>
            </div>
        </div>
    </header>

    <!-- Главный экран (Hero) -->
    <section id="hero">
        <div class="container">
            <h2>Играй в лучшие игры - прямо сейчас!</h2>
            <h3>У нас вы найдете самые популярные игры по выгодным ценам.</h3>-
        </div>
    </section>

    <!-- Популярные игры -->
    <section id="popular-games" class="games-section">
        <div class="container">
            <h2>Популярные игры</h2>
            <div class="games-carousel">
                <div class="games-track">
                    <div class="game">
                        <img src="https://avatars.mds.yandex.net/i?id=22be8b2acdf7a2f2e26852da08a43ea1_l-5222261-images-thumbs&n=13" alt="Grand Theft Auto V">
                        <h3>Grand Theft Auto V</h3>
                        <p>Купить Grand Theft Auto V</p>
                        <p class="price">$16.99</p>
                        <button class="buy-button">Купить</button>
                    </div>
                    <div class="game">
                        <img src="https://digiseller.mycdn.ink/preview/1013858/p1_3708569_a63da01d.png" alt="Minecraft">
                        <h3>Minecraft</h3>
                        <p>Купить ключ активации Minecraft</p>
                        <p class="price">$19.99</p>
                        <button class="buy-button">Купить</button>
                    </div>
                    <div class="game">
                        <img src="https://thehealtheaducation.com/wp-content/uploads/2023/06/Fallout-4-1000x600.jpg" alt="Fallout 4">
                        <h3>Fallout 4</h3>
                        <p>Купить ключ активации Fallout 4</p>
                        <p class="price">$18.99</p>
                        <button class="buy-button">Купить</button>
                    </div>
                    <div class="game">
                        <img src="https://yandex-images.clstorage.net/10BS0P363/f49a6aOZmic/DX7oaceBnKs-f3nwg0ftqhFAXRhl4G5Pig9hNE1tfvXBEidM2nKLM-LNulQisDfYkgf5RCyKwYNJFT6hTuC-jZkufDkQEFyqe227Y4XE6a9CRw3dNWYvTlxMYW6DJaIrD83_x8ctFrX3D20AZaPzHYldad1xk5dejQI3Zp08rlTLsy2vjlnWJ7JgfjJFDGSmhgKVmzSoNU7FEzjliOlpYITP84bFKxf_u0EoAqo1PhzMnvzafFUcVg0HvK9RfeLQCbCkZkMXkai84f1xw4Vmp8_FnR237vtAyJI_Ycmh5iZNyn_LD-vUtjqCqcGqNHaZCJc03T1TEVCCCPGjnfDk0IWwJWFAmVervyF6M4KLqKABSFac8GtxSMlROWPMK67gwk73i81v3Pp6xiCCLfu2FsLXu5D7VJyRz4r7KFDw6lUIvu4lCx_bbjFvfPrNQ-boA4dfWXoudE2OlH5kye4jZwuMfk3GLFE6dsfuiqM4Md3Ik_LS-dWe1ITKvWfYsKpVxzGuYAEQGaj7Zrz9jECnbcsKHd99pntGzV04osYkIifDSv9Dxq-fNrWCYIpjO_zRwBo3VDCeFNNDyDtq1nvpGU754uQF3pumuul--0CNIe-JzZYfeCC6ycZU9W2AbiIjAIo7Ccjr3_GyjuTLbfu7k8Rf8FjyHhcRQYnza5b_ZFuLvWPugBgRafNm-rmEw29ihIKXUHenMIaNnLahhGSmLgjFeUYAY571NgKqCKt78ZREW3gTOd_Q0wSN-KjTvG6Th3rsIEcRFO-47bN9RQwgKAnIEZS2qDuJh92-KkkhpmlJTTXGjm-ccvlO4oMt_vLZD1c3lX8dlRVJA39jnL4s3IM4JGgC2V7gcC3ztoRDLucAxtjZcyJ7wE2edOfBpO6nCEoyi8-iFDo5Aa5Br73_GEgc8BS4GxHbhUuxrNlx4V_DfqwliRLWqzmtPbkIBqEkiIDW2fzivE2Gk_krz4" alt="S.T.A.L.K.E.R. 2">
                        <h3>S.T.A.L.K.E.R. 2</h3>
                        <p>Купить S.T.A.L.K.E.R. 2</p>
                        <p class="price">$24.99</p>
                        <button class="buy-button">Купить</button>
                    </div>
                    <div class="game">
                        <img src="https://digiseller.mycdn.ink/preview/1253594/p1_4170983_a4660bc1.jpg" alt="Cyberpunk 2077">
                        <h3>Cyberpunk 2077</h3>
                        <p>Купить Cyberpunk 2077</p>
                        <p class="price">$18.99</p>
                        <button class="buy-button">Купить</button>
                    </div>
                    <div class="game">
                        <img src="https://steamuserimages-a.akamaihd.net/ugc/1798604548099033527/5C97F09DE417E04FF3B2A75A34E5928C92CFD397/?imw=512&amp;imh=290&amp;ima=fit&amp;impolicy=Letterbox&amp;imcolor=%23000000&amp;letterbox=true" alt="DOOM (2016)">
                        <h3>DOOM (2016)</h3>
                        <p>Купить ключ активации DOOM в steam</p>
                        <p class="price">$5.99</p>
                        <button class="buy-button">Купить</button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Новинки -->
    <section id="new-releases" class="games-section">
        <div class="container">
            <h2>Новинки</h2>
            <div class="games-carousel">
                <div class="games-track">
                    <div class="game">
                        <img src="https://i.ytimg.com/vi/m6PwmZVSivk/maxresdefault.jpg" alt="Prime в CS:GO">
                        <h3>CS:GO</h3>
                        <p>Купить Prime в CS:GO</p>
                        <p class="price">$13.99</p>
                        <button class="buy-button">Купить</button>
                    </div>
                    <div class="game">
                        <img src="https://avatars.mds.yandex.net/i?id=10df005ff1927bd2e230154e09fb6705_l-9068918-images-thumbs&n=13" alt="1000 V-Bucks в Fortnite">
                        <h3>Fortnite </h3>
                        <p>Купить 1000 V-Bucks в Fortnite</p>
                        <p class="price">$9.99</p>
                        <button class="buy-button">Купить</button>
                    </div>
                    <div class="game">
                        <img src="https://www.digiseller.ru/preview/321352/p1_3061360_f5ea7556.png" alt="Steam Wallet">
                        <h3>Steam Wallet </h3>
                        <p>Пополнить Steam Wallet</p>
                        <p class="price">Комисия от суммы 10%</p>
                        <button class="buy-button">Купить</button>
                    </div>
                    <div class="game">
                        <img src="https://xbox-store-checker.com/assets/upload/game/2019/09/optimize/bs5kh5d3qqwv-background.jpg" alt="400 Robux">
                        <h3>Robux</h3>
                        <p>Купить 400 в Robux</p>
                        <p class="price">$5.99</p>
                        <button class="buy-button">Купить</button>
                    </div>
                    <div class="game">
                        <img src="https://playerok.fra1.digitaloceanspaces.com/images/1ed726d8-caaa-69f0-3b3d-25a157d8f511.jpg" alt="80 гемы в Brawl Stars">
                        <h3>Brawl Stars</h3>
                        <p>Купить 80 гемов в Brawl Stars</p>
                        <p class="price">$3.99</p>
                        <button class="buy-button">Купить</button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Акции и скидки -->
    <section id="sales" class="games-section">
        <div class="container">
            <h2>Акции и скидки</h2>
            <div class="games-carousel">
                <div class="games-track">
                    <div class="game">
                        <img src="https://digiseller.mycdn.ink/preview/1070779/p1_3376659_580725c2.jpg" alt="Phasmophobia">
                        <h3>Phasmophobia</h3>
                        <p>Купить Phasmophobia</p>
                        <p class="old-price">$6.99</p>
                        <p class="price">$4.99</p>
                        <button class="buy-button">Купить</button>
                    </div>
                    <div class="game">
                        <img src="https://avatars.mds.yandex.net/get-marketpic/8167191/pic4be0457ebc3add46f84b6cef3f47c233/orig" alt="Metro Exodus DLC sam's story">
                        <h3>Metro Exodus DLC Sam's story</h3>
                        <p>Купить Metro Exodus DLC Sam's story</p>
                        <p class="old-price">$10.99</p>
                        <p class="price">$8.99</p>
                        <button class="buy-button">Купить</button>
                    </div>
                    <div class="game">
                        <img src="https://i.playground.ru/e/aGJls2mxi_FMJhVPrDYIbg.jpeg" alt="Assassin's Creed 2">
                        <h3>Assassin's Creed 2</h3>
                        <p>Купить Assassin's Creed 2</p>
                        <p class="old-price">$20.99</p>
                        <p class="price">$16.99</p>
                        <button class="buy-button">Купить</button>
                    </div>
                    <div class="game">
                        <img src="https://avatars.mds.yandex.net/i?id=4ad9c88eb37a4efd2a6dd39aead2182b_l-11418334-images-thumbs&n=13" alt="Rust">
                        <h3>Rust</h3>
                        <p>Купить защиту от клана китайцев в Rust</p>
                        <p class="old-price">$10.99</p>
                        <p class="price">$5.99</p>
                        <button class="buy-button">Купить</button>
                    </div>
                    <div class="game">
                        <img src="https://i.ytimg.com/vi/ha_sxEjcm1U/maxresdefault.jpg" alt="Atomic Heart">
                        <h3>Atomic Heart</h3>
                        <p>Купить Atomic Heart</p>
                        <p class="old-price">$19.99</p>
                        <p class="price">$17.99</p>
                        <button class="buy-button">Купить</button>
                    </div>
                    <div class="game">
                        <img src="https://steamuserimages-a.akamaihd.net/ugc/1859436274168694166/1327E6C980DEAEFBACA5DEC88AF119951EDB8386/?imw=512&amp;imh=288&amp;ima=fit&amp;impolicy=Letterbox&amp;imcolor=%23000000&amp;letterbox=true" alt="Hearts of Iron IV">
                        <h3>Hearts of Iron IV</h3>
                        <p>Купить Hearts of Iron IV</p>
                        <p class="old-price">$25.99</p>
                        <p class="price">$19.99</p>
                        <button class="buy-button">Купить</button>
                    </div>
                </div>
            </div>
        </div>
    </section>
<!-- Форма для оформления заказа -->
<form id="order-form" class="order-form">
    <h3>Оформление заказа</h3>
    <div class="form-group">
        <label for="login">Логин:</label>
        <input type="text" id="login" name="login" required>
    </div>
    <div class="form-group">
        <label for="password">Пароль:</label>
        <input type="password" id="password" name="password" required>
        <small class="password-hint">Пароль должен содержать только цифры (от 6 до 10 символов).</small>
    </div>
    <button type="submit" class="order-button">Оформить заказ</button>
</form>

    <!-- О нас -->
    <section id="about-us">
        <div class="container">
            <h2>О нас</h2>
            <p>Мы - компания, которая любит игры и хочет поделиться этим с вами. У нас вы найдете лучшие игры по самым выгодным ценам.</p>
            <p>Контакты:</p>
            <ul>
                <li>Телефон: +7 (928) 711-25-87</li>
                <li>Email: GameSell@gmail.com</li>
                <li>Адрес: г. Нальчик, ул. Орджаникидзе, д. 172</li>
            </ul>
        </div>
    </section>

    <!-- Футер -->
    <footer>
        <div class="container">
            <p>&copy; 2024 GameSell. Все права защищены.</p>
        </div>
    </footer>

    <script src="GameSell2.js"></script>
    <script src="GameSell1.js"></script>
</body>
</html>
