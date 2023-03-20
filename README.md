<html lang="en"><head>
    <meta charset="UTF-8">
    <title>Портфолио WEB-разработчика</title>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body { margin: 0 auto; padding: 0px; font-family: 'Akrobat'; } .bgcolor { width: 100%; height: 100%; z-index: -100; position: absolute; } .logotype { max-width: 200px; max-height: 150px; margin-top: 70px; position: relative; z-index: 20; } .caption { z-index: 20; } .caption h4 { color: #f8b410; text-transform: uppercase; letter-spacing: 2px; font-family: 'Akrobat'; margin-top: 90px; font-weight: bold; } .btn { width: 60px; height: 60px; background-color: black; position: fixed; z-index: 100; cursor: pointer; top: 70px; } .btn div { display: block; } .btn:before, .btn:after { content: ""; position: absolute; width: 0; height: 0; opacity: 0; -webkit-box-sizing: border-box; -o-box-sizing: border-box; box-sizing: border-box; } .btn:before { bottom: 0; left: 0; border-left: 1px solid white; border-top: 1px solid white; border-radius: 4px; -webkit-transition: 0s ease opacity .8s, .2s ease width .4s, .2s ease height .6s; -o-transition: 0s ease opacity .8s, .2s ease width .4s, .2s ease height .6s; transition: 0s ease opacity .8s, .2s ease width .4s, .2s ease height .6s; } .btn:after { top: 0; right: 0; border-right: 1px solid white; border-bottom: 1px solid white; border-radius: 4px; -webkit-transition: 0s ease opacity .4s, .2s ease width, .2s ease height .2s; -o-transition: 0s ease opacity .4s, .2s ease width, .2s ease height .2s; transition: 0s ease opacity .4s, .2s ease width, .2s ease height .2s; } .btn:hover:before, .btn:hover:after { height: 100%; width: 100%; opacity: 1; } .btn:hover:before { -webkit-transition: 0s ease opacity 0s, .2s ease height, .2s ease width .2s; -o-transition: 0s ease opacity 0s, .2s ease height, .2s ease width .2s; transition: 0s ease opacity 0s, .2s ease height, .2s ease width .2s; } .btn:hover:after { -webkit-transition: 0s ease opacity .4s, .2s ease height .4s, .2s ease width .6s; -o-transition: 0s ease opacity .4s, .2s ease height .4s, .2s ease width .6s; transition: 0s ease opacity .4s, .2s ease height .4s, .2s ease width .6s; } .sandwich { width: 45px; height: 22px; position: absolute; top: 17px; left: 7px; z-index: 150; } .sw-top, .sw-mid, .sw-foot { width: 45px; height: 3px; background: #ffffff; position: relative; border: none; } .sw-top { top: 1px; background: rgb(255, 255, 255); border: none; border-radius: 4px 4px 4px 4px; -webkit-transition: top 0.2s, -webkit-transform 0.5s; transition: top 0.2s, -webkit-transform 0.5s; -o-transition: transform 0.5s, top 0.2s; transition: transform 0.5s, top 0.2s; transition: transform 0.5s, top 0.2s, -webkit-transform 0.5s; transition: transform 0.5s, top 0.2s, -webkit-transform 0.5s; } .sw-mid { top: 7px; background: rgb(255, 255, 255); border: none; border-radius: 4px 4px 4px 4px; -webkit-transition: top 0.2s, -webkit-transform 0.5s; transition: top 0.2s, -webkit-transform 0.5s; -o-transition: transform 0.5s, top 0.2s; transition: transform 0.5s, top 0.2s; transition: transform 0.5s, top 0.2s, -webkit-transform 0.5s; } .sw-foot { top: 13px; background: rgb(255, 255, 255); border: none; border-radius: 4px 4px 4px 4px; -webkit-transition: all 0.5s; -o-transition: all 0.5s; transition: all 0.5s; -webkit-transition-delay: 0.1s; -o-transition-delay: 0.1s; transition-delay: 0.1s; } .top-txt { position: absolute; width: 100% !important; height: 100% !important; top: 0; left: 0; } .top-sur:before { content: ""; display: inline-block; height: 40%; vertical-align: middle; } .top-sur { height: 100%; } .top-sur div { vertical-align: middle; } .sandwich.active .sw-top { top: 10px; -webkit-transform: rotate(135deg); -ms-transform: rotate(135deg); transform: rotate(135deg); } .sandwich.active .sw-mid { top: 7px; -webkit-transform: rotate(-135deg); -ms-transform: rotate(-135deg); transform: rotate(-135deg); } .sandwich.active .sw-foot { opacity: 0; top: 0; -webkit-transform: rotate(180deg); -ms-transform: rotate(180deg); transform: rotate(180deg); } .top-sur h1 { color: #f8b410; text-transform: uppercase; border: 4px solid #fff; padding: 15px 20px; font-family: 'Akrobat'; letter-spacing: 3px; margin-bottom: 150px; display: inline-block; } .top-txt p { color: #f8b410; font-size: 18px; font-family: 'Akrobat'; letter-spacing: 3px; font-weight: bold; display: inline-block; text-align: center; }
    </style>
    <link rel="stylesheet" href="css/bootstrap.css">
    <link rel="stylesheet" href="css/media.css">
    <link rel="icon" type="images/x-icon" href="img/logo.ico">
    <!--chart-->
    <script src="js/jquery-3.2.1.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script src="js/jquery.malihu.PageScroll2id.min.js"></script>
    <script src="js/common.js"></script>
</head>
<body>
    <div class="wrapper">
        <!-- ШАПКА -->
        <header id="header" class="_mPS2id-t" style="min-height: 600px;">
            <img src="img/bg.png" alt="Фон" class="bgcolor">
            <div class="container">
                <div class="row">
                    <div class="col-md-2 col-sm-2 col-xs-4 logotype">
                        <a href="https://readycodeee.github.io/"><img src="img/logo.png" alt="Логотип">&nbsp;</a>
                    </div>
                    <div class="col-md-offset-1 col-sm-6 col-sm-offset-1 col-xs-10 col-xs-offset-1 caption text-center wow fadeInDown" data-wow-offset="150" style="visibility: visible; animation-name: fadeInDown;">
                        <h4 class="titl">САЙТ-ПОРТФОЛИО веб-разработчика</h4>
                    </div>
                    <div class="btn col-md-offset-2 col-lg-offset-2 col-sm-offset-2 col-xs-offset-5" autofocus="">
                        <div class="sandwich">
                            <div class="sw-top"></div>
                            <div class="sw-mid"></div>
                            <div class="sw-foot"></div>
                        </div>
                    </div>
                    <div class="menu" style="display: none;">
                        <ul class="fadeInUp animated">
                            <li><a href="#header" rel="m_PageScroll2id" class="__mPS2id _mPS2id-h">Главная<span></span></a></li>
                            <li><a href="#about" rel="m_PageScroll2id" class="__mPS2id _mPS2id-h mPS2id-highlight mPS2id-highlight-first mPS2id-highlight-last">Обо мне<span></span></a></li>
                            <li><a href="#portfolio" rel="m_PageScroll2id" class="__mPS2id _mPS2id-h">Портфолио<span></span></a></li>
                            <li><a href="#contacts" rel="m_PageScroll2id" class="__mPS2id _mPS2id-h">Контакты<span></span></a></li>
                        </ul>
                    </div>
                    <div class="top-txt">
                        <div class="top-sur text-center">
                            <div>
                                <h1>кулинич иван</h1>
                            </div>
                            <div>
                                <p class="top-text wow fadeInUp" data-wow-offset="150" style="visibility: visible; animation-name: fadeInUp;">WEB-РАЗРАБОТЧИК / HTML-ВЕРСТАЛЬЩИК</p>
                                <br>
                                <p class="top-text wow fadeInUp" data-wow-offset="150" style="visibility: visible; animation-name: fadeInUp;">ПРОГРАММИСТ PHP / JAVASCRIPT</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </header>
        <!-- ОБО МНЕ -->
        <section id="about" class="_mPS2id-t mPS2id-target mPS2id-target-first mPS2id-target-last">
            <div class="container">
                <div class="about">
                    <div class="row">
                        <div class="content text-center">
                            <div class="wow fadeInUp" data-wow-offset="150" style="visibility: visible; animation-name: fadeInUp;">
                                <h2>Обо мне</h2>
                                <hr>
                            </div>
                            <div class="some-about col-lg-4 col-md-4 col-sm-4 wow fadeInLeft" data-wow-offset="150" style="visibility: visible; animation-name: fadeInLeft;">
                                <h3>Немного о себе</h3>
                                <img src="img/me1.png" alt="Лист" class="me1 ">
                                <p>Доброго времени суток,меня зовут Сергей
                                    <br> Я прохожу обучение на курсе Нетология Инженер по тестированию: с нуля до middle.
                                    <br> Выполняю верстку и программирование сайтов,а так же доработку,добавляя полный функционал на сайт! Верстаю адаптивную верстку с помощью Bootstrap,
                                    <br>таким образом сайт получается красивым на любом устройстве,будь то комьютер,ноутбук или телефон!
                                </p>
                            </div>
                            <div class="knowledge col-lg-4 col-md-4 col-sm-4 wow fadeInUp" data-wow-offset="150" style="visibility: visible; animation-name: fadeInUp;">
                                <h3>Знания и Умения</h3>
                                <img src="img/me2.png" alt="лист" class="me2">
                                <p>Изучаю такие языки программирования,как: PHP, JavaScript. Языки разметки: HTML(5), таблицы стилей CSS(3).
                                    <br>Учусь верстать адаптивные сайты под планшеты и мобильные устройства, фраемворк Bootstrap. </p>
                            </div>
                            <div class="self col-lg-4 col-md-4 col-sm-4 wow fadeInRight" data-wow-offset="150" style="visibility: visible; animation-name: fadeInRight;">
                                <h3>Самообразование</h3>
                                <img src="img/me3.png" alt="лист" class="me3">
                                <p>Курсы в интернете, видеокурсы, книги, документация, форумы, статьи...</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="skils text-center">
                    <div class="container">
                        <div class="row">
                            <div class="top-text-ab wow fadeInUp" data-wow-offset="150" style="visibility: hidden; animation-name: none;">
                                <h2>Профессиональные навыки</h2>
                                <hr>
                            </div>
                            <div class="col-lg-3 col-md-3 col-sm-3 col-xs-6">
                                <h4>HTML5|CSS3</h4>
                                <div id="test-circle1" class="svg-container"><svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 194 186" class="circliful">undefined<text text-anchor="middle" x="100" y="115" style="null" fill="#333">HTML</text><circle cx="100" cy="100" r="57" class="border" fill="#eee" stroke="none" stroke-width="15" stroke-dasharray="360" transform="rotate(-90,100,100)"></circle><circle class="circle" cx="100" cy="100" r="57" fill="none" stroke="#f8b410" stroke-width="5" stroke-dasharray="288, 20000" transform="rotate(-90,100,100)"></circle><circle cx="100" cy="100" r="28.5" fill="none"></circle>undefined<text class="timer" text-anchor="middle" x="100" y="110" style="font-size: 22px; undefined;" fill="#aaa">80%</text></svg></div>
                            </div>
                            <div class="col-lg-3 col-md-3 col-sm-3 col-xs-6">
                                <h4>jQuery|JavaScript</h4>
                                <div id="test-circle2" class="svg-container"><svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 194 186" class="circliful">undefined<circle cx="100" cy="100" r="57" class="border" fill="#eee" stroke="none" stroke-width="15" stroke-dasharray="360" transform="rotate(-90,100,100)"></circle><circle class="circle" cx="100" cy="100" r="57" fill="none" stroke="#3498DB" stroke-width="5" stroke-dasharray="270, 20000" transform="rotate(-90,100,100)"></circle><circle cx="100" cy="100" r="28.5" fill="none"></circle>undefined<text class="timer" text-anchor="middle" x="100" y="110" style="font-size: 22px; undefined;" fill="#aaa">75%</text></svg></div>
                            </div>
                            <div class="col-lg-3 col-md-3 col-sm-3 col-xs-6">
                                <h4>PHP|MySQL</h4>
                                <div id="test-circle3" class="svg-container"><svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 194 186" class="circliful">undefined<circle cx="100" cy="100" r="57" class="border" fill="#eee" stroke="none" stroke-width="15" stroke-dasharray="360" transform="rotate(-90,100,100)"></circle><circle class="circle" cx="100" cy="100" r="57" fill="none" stroke="#333" stroke-width="5" stroke-dasharray="216, 20000" transform="rotate(-90,100,100)"></circle><circle cx="100" cy="100" r="28.5" fill="none"></circle>undefined<text class="timer" text-anchor="middle" x="100" y="110" style="font-size: 22px; undefined;" fill="#aaa">60%</text></svg></div>
                            </div>
                            <div class="col-lg-3 col-md-3 col-sm-3 col-xs-6">
                                <h4>Photoshop</h4>
                                <div id="test-circle4" class="svg-container"><svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 194 186" class="circliful">undefined<circle cx="100" cy="100" r="57" class="border" fill="#eee" stroke="none" stroke-width="15" stroke-dasharray="360" transform="rotate(-90,100,100)"></circle><circle class="circle" cx="100" cy="100" r="57" fill="none" stroke="#f8b410" stroke-width="5" stroke-dasharray="363.6, 20000" transform="rotate(-90,100,100)"></circle><circle cx="100" cy="100" r="28.5" fill="none"></circle>undefined<text class="timer" text-anchor="middle" x="100" y="110" style="font-size: 22px; undefined;" fill="#aaa">101%</text></svg></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- ПОРТФОЛИО-->
        <section id="portfolio" class="_mPS2id-t">
            <div class="container">
                <div class="row">
                    <div class="article-potf text-center">
                        <div class="top-text-pt wow fadeInUp" data-wow-offset="150" style="visibility: hidden; animation-name: none;">
                            <h2>Портфолио</h2>
                            <hr>
                        </div>
                        <div class="top-menu-pt">
                            <div class="col-md-12 col-sm-12 col-xs-12">
                                <div class="top-menu filter_div controls">
                                    <ul class="inline">
                                        <li class="wow bounceInLeft filter active" type="button" data-filter=".all" style="visibility: hidden; animation-name: none;">Все работы</li>
                                        <li class="wow bounceInLeft filter" type="button" data-filter=".category-1" style="visibility: hidden; animation-name: none;">"под ключ"</li>
                                        <li class="wow bounceInRight filter" type="button" data-filter=".category-2" style="visibility: hidden; animation-name: none;">Верстка</li>
                                        <li class="wow bounceInRight filter" type="button" data-filter=".category-3" style="visibility: hidden; animation-name: none;">Прочее</li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                        <div id="Container" class="content-potfol container">
                            <div class="mix all category-2  category-3 col-lg-3 col-md-3 col-sm-3 col-xs-6 work-cont">
                                <img src="img/work1.png" alt="Пример" class="work">
                                <div class="port-item-cont">
                                    <h4>Птицефабрика Буртеско</h4>
                                    <p>Краткое описание</p>
                                    <button type="button" class="btn-more" data-toggle="modal" data-target="#modal-1">Подробнее</button>
                                </div>
                            </div>
                            <div class="mix all category-2 col-lg-3 col-md-3 col-sm-3 col-xs-6 work-cont">
                                <img src="img/work2.png" alt="Пример" class="work">
                                <div class="port-item-cont">
                                    <h4><br>Бетховен</h4>
                                    <p>Краткое описание</p>
                                    <button type="button" class="btn-more" data-toggle="modal" data-target="#modal-2">Подробнее</button>
                                </div>
                            </div>
                            <div class="mix all category-1 category-3 category-2 col-lg-3 col-md-3 col-sm-3 col-xs-6 work-cont">
                                <img src="img/work3.png" alt="Пример" class="work">
                                <div class="port-item-cont">
                                    <h4><br>Земной шар</h4>
                                    <p>Краткое описание</p>
                                    <button type="button" class="btn-more" data-toggle="modal" data-target="#modal-3">Подробнее</button>
                                </div>
                            </div>

                            <div class="mix all category-2 col-lg-3 col-md-3 col-sm-3 col-xs-6 work-cont">
                                <img src="img/work4.png" alt="Пример" class="work">
                                <div class="port-item-cont">
                                    <h4><br>Portfolio</h4>
                                    <p>Краткое описание</p>
                                    <button type="button" class="btn-more" data-toggle="modal" data-target="#modal-4">Подробнее</button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!--КОНТАКТЫ-->
        <section id="contacts" class="_mPS2id-t">
            <div class="container">
                <div class="row">
                    <div class="cont-comm text-center">
                        <div class="top-text-comm wow fadeInUp" data-wow-offset="150" style="visibility: hidden; animation-name: none;">
                            <h2>Контакты</h2>
                            <hr>
                            <h4>Если у вас есть вопросы, я с радостью отвечу на них!<br> 
Для этого свяжитесь со мной удобным для вас способом и я отвечу Вам в ближайшее время!</h4>
                        </div>
                        <div class="info">
                            <div class="col-md-3 col-sm-3 col-xs-6 wow bounceInLeft" data-wow-offset="100" style="visibility: hidden; animation-name: none;">
                                <div class="contact-box">
                                    <div class="contacts-icon">
                                        <i class="fa fa-envelope-o" aria-hidden="true"></i>
                                    </div>
                                    <h4>E-mail:</h4>
                                    <p>test@gmail.com</p>
                                </div>
                                <div class="contact-box">
                                    <div class="contacts-icon">
                                        <i class="fa fa-vk" aria-hidden="true"></i>
                                    </div>
                                    <h4>Вконтаке:</h4>
                                    <a href="https://vk.com/vanchoice">https://vk.com/test</a>
                                </div>
                                <div></div>
                            </div>
                            <div class="col-md-3 col-sm-3 col-xs-6 wow bounceInLeft" data-wow-offset="100" style="visibility: hidden; animation-name: none;">
                                <div class="contact-box">
                                    <div class="contacts-icon">
                                        <i class="fa fa-desktop" aria-hidden="true"></i>
                                    </div>
                                    <h4>Web-сайт:</h4>
                                    <a href="readycodeee.github.io">test.github.io</a>
                                </div>
                                <div class="contact-box">
                                    <div class="contacts-icon">
                                        <i class="fa fa-skype" aria-hidden="true"></i>
                                    </div>
                                    <h4>Skype:</h4>
                                    <p>test</p>
                                </div>
                            </div>

                            <div class="col-md-6 col-sm-6 col-xs-12 wow bounceInRight" data-wow-offset="100" style="visibility: hidden; animation-name: none;">
                                <div class="top-text-message">
                                    <h4>Так же Вы можете написать свое сообщения прямо здесь!<br>Вам необходио заполнить все поля!</h4>
                                </div>
                                <div class="message">
                                    <form method="post" action="https://formspree.io/zollex69@gmail.com">
                                        <p>Ваше имя
                                            <br>
                                            <input type="text" size="32" required="" name="your_name" placeholder="Ваше имя">
                                        </p>
                                        <p>Ваш E-mail
                                            <br>
                                            <input type="email" size="32" required="" name="email" placeholder="example@mail.com">
                                        </p>
                                        <p>Ваше сообщение
                                            <br>
                                            <textarea type="text" name="comment" cols="34" rows="5" placeholder="Ваше сообщение"></textarea>
                                        </p>
                                        <p>
                                            <input type="submit" value="Send" class="btn-sub">
                                    </p></form>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!--ПОДВАЛ-->
        <footer>
            <div class="container">
                <div class="row">
                    <div class="col-md-5 col-sm-5 col-xs-10">
                        <div class="text-info">
                            <p>© 2023 Сергей. Стремимся к совершенству, при создание сайтов</p>
                        </div>
                    </div>
                    <div class="col-md-1 col-sm-1 col-xs-1 col-md-offset-6 col-sm-offset-6">
                        <div class="social">
                            <a href="https://vk.com/test">
                                <i class="fa fa-vk" aria-hidden="true"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </footer>
    </div>


    <div class="modal" id="modal-1">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header text-center">
                    <h3 class="modal-title">Подробнее</h3>
                    <button class="close" type="button" data-dismiss="modal">
                        <i class="fa fa-close"></i>
                    </button>
                </div>
                <div class="modal-body text-center">
                    <div class="img-content">
                        <img src="img/pic-more1.png" alt="Бунровский Дом">
                    </div>
                </div>
                <div class="modal-footer">
                    <button class="btn-danger" type="button" data-dismiss="modal">Закрыть</button>
                </div>
            </div>
        </div>
    </div>
    <div class="modal" id="modal-2">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header text-center">
                    <h3 class="modal-title">Подробнее</h3>
                    <button class="close" type="button" data-dismiss="modal">
                        <i class="fa fa-close"></i>
                    </button>
                </div>
                <div class="modal-body text-center">
                    <div class="img-content">
                        <img src="img/pic-more2.png" alt="Картинка сайта">
                    </div>
                </div>
                <div class="modal-footer">
                    <button class="btn-danger" type="button" data-dismiss="modal">Закрыть</button>
                </div>
            </div>
        </div>
    </div>
    <div class="modal" id="modal-3">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header text-center">
                    <h3 class="modal-title">Подробнее</h3>
                    <button class="close" type="button" data-dismiss="modal">
                        <i class="fa fa-close"></i>
                    </button>
                </div>
                <div class="modal-body text-center">
                    <div class="img-content">
                        <img src="img/pic-more3.png" alt="Картинка сайта">
                    </div>
                </div>
                <div class="modal-footer">
                    <button class="btn-danger" type="button" data-dismiss="modal">Закрыть</button>
                </div>
            </div>
        </div>
    </div>
    <div class="modal" id="modal-4">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header text-center">
                    <h3 class="modal-title">Подробнее</h3>
                    <button class="close" type="button" data-dismiss="modal">
                        <i class="fa fa-close"></i>
                    </button>
                </div>
                <div class="modal-body text-center">
                    <div class="img-content">
                        <img src="img/pic-more4.png" alt="Картинка сайта">
                    </div>
                </div>
                <div class="modal-footer">
                    <button class="btn-danger" type="button" data-dismiss="modal">Закрыть</button>
                </div>
            </div>
        </div>
    </div>

<link rel="stylesheet" href="css/style.css">
<link rel="stylesheet" href="css/animate.css">
<link rel="stylesheet" href="css/jquery.circliful.css">
<link rel="stylesheet" href="css/font-awesome.min.css">
<script src="js/jquery.circliful.min.js"></script>
<script src="js/wow.min.js"></script>
<script src="js/mixitup.min.js"></script>


</body></html>