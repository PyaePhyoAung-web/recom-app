<template>
  <div class="hello">
    <!-- Navbar Section -->
    <nav class="navbar">
        <div class="navbar__container">
          <a href="#home" id="navbar__logo">RECOM-APP</a>
          <div class="navbar__toggle" id="mobile-menu">
            <span class="bar"></span> 
            <span class="bar"></span>
            <span class="bar"></span>
          </div>

          <ul class="navbar__menu">
            <li class="navbar__item">
              <a href="#home" class="navbar__links" id="home-page">Дом</a>
            </li>
            <li class="navbar__item">
              <a href="#services" class="navbar__links" id="services-page">Веб-сайты</a>
            </li>
            <li class="navbar__item">
              <a href="#about" class="navbar__links" id="about-page">Выбор</a>
            </li>
            <li class="navbar__btn">
              <a href="#sign-up" class="button" id="signup">Войти</a>
            </li>
          </ul>
        </div>
    </nav>
    <!-- Hero Section -->
    <div class="hero" id="home">
        <div class="hero__container">  
          <h1 class="hero__heading">Система рекомендаций по выбору <span>веб-ресурсов</span> по предпринимательству</h1>
          <img src="../assets/ig.jpeg" alt="" width="800" height="450" >
    </div>

    <!-- Services Section -->
    <div class="services" id="services">
        <h1>Типы веб-сайтов</h1>
        <h3>1. Сайт-визитка</h3>
        <div class="a">
        <p>Сайт-визитка обычно состоит из нескольких страниц, на которых дается краткая информация о компании, предоставляемых ей услугах и контактах. Основными преимуществами сайта-визитки являются низкая стоимость создания и быстрый запуск, а недостатками –низкий функционал и бедный дизайн. Веб-сайт магазина «Антиквариат» имеет небольшой объем информации по спецификации и деятельности магазина и простой, но достаточно приятный дизайн. Интернет-ресурс компании ООО «Три-Р» также является сайтом визиткой, при чем довольно высокого уровня. Удобный и приятный дизайн, наличие галереи товаров,а также возможность оформления заказа через сайт – те достоинства, которые могут привлечь клиента. Если нужно проинформировать людей о вашей организации, можно выбрать этот тип веб-сайта.</p>
        </div>
        <br>

        <h3>2. Корпоративный сайт</h3>
        <div class="a">
        <p>Корпоративный сайт - это многофункциональный сайт компании, создающийся как для информирования клиентов, так и для непосредственного преследования коммерческих целей. Корпоративный сайт представляет собой улучшенная версия сайта визитки. На нем обычно присутствуют своевременно обновляющаяся лента новостей, функция поиска, фотогалереи, формы для обратной связи с клиентами (отзывов, заявок). У сайта «РОСНЕФТЬ» удобный и стильный интерфейс, имеется раздел отзывов и предложений, возможность поиска по сайту, ссылка на сообщество в социальной сети «Вконтакте» и множество полезной информации по сфере деятельности организации. Плюсом является возможность создания для пользователей личного кабинета. У медицинского центра «Диамед» сайт содержит функцию «Вопрос доктору». У сайтов корпоративного типа обычно нет явных недостатков - они хорошо выполняют свои функции привлечения новых клиентов и поддержки уже существующих, но все же не имеют такого полного функционала, как следующий вид веб-сайтов.</p>
        </div>
        <br>

        <h3>3. Портал</h3>
        <div class="a">
        <p>Портал сайт ориентирован на обеспечение удобства клиентов всеми возможными способами. К функциональности портала относятся размещение фото, аудио и видео в виде специальных галерей, просмотр и прослушивание онлайн, форумы, блоги, рейтинги и голосования, система управления комментариями и обменом сообщениями между пользователями и так далее. Главная черта портала – очень активное взаимодействие с пользователем.Примером портала является образовательный ИТ-портал «GeekBrains», на котором учат людей с нуля осваивать программирование, веб-дизайн и маркетинг. Для этого на сайте проводятся онлайн-курсы со стажировкой и бесплатные мастер классы. Зарегистрировавшись на сайте, пользователи могут проходить тесты, смотреть вебинары, пользоваться форумом и вести свой блог. В разделе блога можно голосовать за лучшие статьи и самому набирать рейтинг, а также оставлять комментарии. И, как и все порталы, данный сайт имеет все черты корпоративного сайта. ИТ-портал очень удобен для людей, желающих получить знания в сфере ИТ.</p>
    </div>
        <br>

        <h3>4. Сайт-сервис</h3>
        <div class="a">
        <p>Сайт-сервис сконцентрирован на решении конкретной потребности клиента, либо нескольких однотипных потребностей. Типичным примером сервиса являются онлайн-консультанты, которые отвечают на вопрос введенный в всплывающем окне. Но такие функции сегодня встроены на каждом портале и на многих корпоративных сайтах. Есть же веб-ресурсы, полностью посвященные оказанию какой-либо услуги. Например, онлайн-школы, как школа английского языка «Skyeng». В ней работают профессионалы, помогающие жителям современных мегаполисов выучить английский язык в условиях недостатка времени. Школа проводит курсы английского языка, предоставляет возможность заниматься с репетитором онлайн, проводить обучение по скайпу. Уроки регулярные, преподавателя может выбрать сам пользователь. После окончания курса и сдачи экзамена клиенту выдается сертификат, и даются рекомендации для трудоустройства. Также существует огромное количество различных онлайн-курсов различных областей знаний, тренингов и семинаров, курсов переподготовки специалистов.</p>
    </div>
        <br>

        <h3>5. Сайт-каталог</h3>
        <div class="a">
        <p>Под каталогом понимается ресурс с витриной из товаров, где приводится их подробное описание, цена, зачастую даже существует возможность оставить отзывы о конкретных позициях, но нет возможности добавить товар в «корзину» и оформить заказ. Компания кухонной мебели «Зов» на своем сайте , представила каталог своих изделий, где можно посмотреть фото кухонь, их описание и параметры, примерную цену, а также поставить оценку. Известный сетевой магазин одежды «Zolla» тоже выбрал для своего веб ресурса вид каталога. Кроме фотографий изделий и цены на сайте для удобства поиска нужной вещи есть удобный фильтр. Также имеется возможность выбрать размер вещи и посмотреть, есть ли она в наличии в конкретном магазине. После регистрации можно добавлять изделия в список избранного.Сайт-каталог является разновидностью сайта-визитки или корпоративного сайта. По концепции, каталогу не хватает очень важной в наше время функции – возможности купить товар в любое время, не выходя из дома.</p>
    </div>
        <br>

        <h3>6. Интернет-магазин</h3>
        <div class="a">
        <p>Интернет-магазин - это самый популярный на данный момент вид коммерции в Интернете. Основная задача электронного магазина — это представление широкого ассортимента и возможности купить товар или услугу непосредственно на сайте. Чем сильнее компания облегчает клиенту жизнь, тем больше клиентов у нее становится. По своей форме все интернет-магазины очень похожи. Они очень напоминают портал: там также есть личный кабинет, возможность взаимодействия с другими пользователями, обратная связь и большое количество информации о компании и ее сфере деятельности. Но, конечно же, то что отличает интернет-магазин от всех других сайтов – факт покупки товара непосредственно на сайте. Оформление заказа осуществляется по типичной схеме: клиент выбирает товар, «складывает» его в Корзину, оформляет заказ, выбирает способ доставки и способ оплаты (оплата иногда осуществляется непосредственно при получении, а не на самом сайте). Примерами интернет-магазинов являются сайты всеми известных компаний: магазин электроники и бытовой техники «Эльдорадо» , магазин одежды и обуви «Lamoda» , книжный магазин «Читай-город» и многие другие.</p>
    </div>
        <br>

        <h3>7. Лендинг</h3>
        <div class="a">
        <p>Промо-сайт или лендинг используют в качестве эффективного инструмента продвижения какого-то одного продукта, услуги, акции, мероприятия. Это одностраничный тип сайта для захвата внимания клиента для последующего выполнения им целевого действия. Минимум всего отвлекающего: на лендинге размещается только ключевая информация, которая способна заинтересовать и побудить сделать покупку товара или заказать услуги. Их, как правило, отличает эффектный дизайн, наличие видеопрезентаций, качественных изображений продукта, его 3D-моделей. Примерами промо-сайтов являются онлайн-интерактивная платформа, которая предлагает бесплатные уроки кодирования Codeacademy и реклама юридических услуг Адвекон Юц.</p>
        
    </div><br>

        <h3>8. Социальные сети</h3>
        <div class="a">
        <p>Мало какая компания может позволить себе собственную социальную сеть, но у любой фирмы есть возможность создать страницу или сообщество в уже существующих. Так делают множество организаций малого бизнеса, у которых нет возможности создать собственный сайт, и даже все те компании, у которых есть довольно хорошие веб- ресурсы, имеют представительства во многих социальных сетях, непременно указывая на основном сайте ссылки на них. Социальная сеть – это бесплатный и довольно эффективный инструмент маркетинга, ведь большинство людей проводит в них очень много времени. К тому же социальные сети предоставляют возможность более интерактивного общения компаний со своими клиентами, ведь основу этих сетей составляют именно коммуникации людей друг с другом. Примеры представительств компаний в социальной сети «Вконтакте»: - группа ювелирного магазина «Sunlight»; - сообщество книжного магазина «Читай-город»; - группа кинотеатра «Мадагаскар» в г. Саранск.</p>
    </div>
    </div>

    <!-- About Section -->
    <div class="main" id="about">
        <div class="main__content">
          <h1>Как выбрать ресурс?</h1>
          <div class="a">
          <p>Кажется, что при таком разнообразии видов сайтов, сделать выбор для своей компании будет очень сложно. Но это не так. Все зависит от функционального назначения планируемого сайта.<br>Этапы следующие:<br><b>1) Определить цель, для которой создается веб-ресурс,<br> 2) Выбрать вид,<br> 3) Выбрать структуру,<br> 4) Выбрать функции,<br> 5) Выбрать дизайн и т.д.</b><br>Если нужно проинформировать людей о вашей организации, тогда стоит выбрать сайт-визитку, корпоративный сайт или даже портал. Компания занимается продажей товаров или услуг? Значит, стоить обратить внимание на сайт-каталог, интернет-магазин или же лендинг. Если вы хотите оказывать услуги онлайн, непосредственно через сайт, значит, вам нужен сайт-сервис</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Features Section -->
    <div class="main" id="sign-up">
        <div class="main__container">
          <div class="main__content">
            <h1>ПРИСОЕДИНИТЬСЯ К НАШЕЙ КОМАНДЕ</h1>
            <h2>Зарегистрироваться Сегодня</h2>
            <p>Посмотрите, что отличает нас</p>
            <button class="main__btn"><a href="login.html">Войти</a></button>
          </div>
          <div class="main__img--container">
            <div class="main__img--card" id="card-2">
              <i class="fas fa-users"></i>
            </div>
          </div>
        </div>
      </div>

    <!-- Footer Section -->
    <div class="footer__container">
        <div class="footer__links">
          <div class="footer__link--wrapper">
            <div class="footer__link--items">
              <h2>О нас</h2>
              <a href="/">Как это устроено</a> 
              <a href="/">Карьера</a> 
              <a href="/">Условия обслуживания</a>
            </div>
            <div class="footer__link--items">
              <h2>Связаться с нами</h2>
              <a href="/">Контакт</a> 
              <a href="/">Поддерживать</a>
              <a href="/">Направления</a>
            </div>
            </div>
            <div class="footer__link--wrapper">
            <div class="footer__link--items">
              <h2>Видео</h2>
              <a href="/">Отправить видео</a>
              <a href="/">Агентство</a>
            </div>
            <div class="footer__link--items">
              <h2>Социальные сети</h2>
              <a href="/">Инстаграм</a> 
              <a href="/">Фейсбук</a>
              <a href="/">Youtube</a> 
              <a href="/">Твиттер</a>
            </div>
          </div>
        </div>
        <section class="social__media">
          <div class="social__media--wrap">
            <div class="footer__logo">
              <a href="/" id="footer__logo">RECOM-APP</a>
            </div>
            <p class="website__rights">© RECOM-APP 2021. Все права защищены.</p>
            <div class="social__icons">
              <a href="https://www.facebook.com/profile.php?id=100016143541450" class="social__icon--link" target="_blank"
                ><i class="fab fa-facebook"></i
              ></a>
              <a href="https://www.instagram.com/phyolay051996/" class="social__icon--link"
                ><i class="fab fa-instagram"></i
              ></a>
              <a href="https://www.youtube.com/" class="social__icon--link"
                ><i class="fab fa-youtube"></i
              ></a>
              <a href="/" class="social__icon--link"
                ><i class="fab fa-linkedin"></i
              ></a>
              <a href="https://twitter.com/home?lang=en" class="social__icon--link"
                ><i class="fab fa-twitter"></i></a>
            </div>
          </div>
        </section>
      </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: 'Kumbh Sans', sans-serif;
  scroll-behavior: smooth;
}

div.a {
  text-indent: 60px;
}

.navbar {
  background: #131313;
  height: 80px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 1.2rem;
  position: sticky;
  top: 0;
  z-index: 999;
}

.navbar__container {
  display: flex;
  justify-content: space-between;
  height: 80px;
  z-index: 1;
  width: 100%;
  max-width: 1300px;
  margin: 0 auto;
  padding: 0 50px;
}

#navbar__logo {
  background-color: #ff8177;
  background-image: linear-gradient(to top, #ff0844 0%, #ffb199 100%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
  display: flex;
  align-items: center;
  cursor: pointer;
  text-decoration: none;
  font-size: 2rem;
}

.navbar__menu {
  display: flex;
  align-items: center;
  list-style: none;
}

.navbar__item {
  height: 80px;
}

.navbar__links {
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 125px;
  text-decoration: none;
  height: 100%;
  transition: all 0.3s ease;
}

.navbar__btn {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0 1rem;
  width: 100%;
}

.button {
  display: flex;
  justify-content: center;
  align-items: center;
  text-decoration: none;
  padding: 10px 20px;
  height: 100%;
  width: 100%;
  border: none;
  outline: none;
  border-radius: 4px;
  background: #833ab4;
  background: -webkit-linear-gradient(to right, #fcb045, #fd1d1d, #833ab4);
  background: linear-gradient(to right, #fcb045, #fd1d1d, #833ab4);
  color: #fff;
  transition: all 0.3s ease;
}

.navbar__links:hover {
  color: #9518fc;
  transition: all 0.3s ease;
}

@media screen and (max-width: 960px) {
  .navbar__container {
    display: flex;
    justify-content: space-between;
    height: 80px;
    z-index: 1;
    width: 100%;
    max-width: 1300px;
    padding: 0;
  }

  .navbar__menu {
    display: grid;
    grid-template-columns: auto;
    margin: 0;
    width: 100%;
    position: absolute;
    top: -1000px;
    opacity: 1;
    transition: all 0.5s ease;
    z-index: -1;
  }

  .navbar__menu.active {
    background: #131313;
    top: 100%;
    opacity: 1;
    transition: all 0.5s ease;
    z-index: 99;
    height: 60vh;
    font-size: 1.6rem;
  }

  #navbar__logo {
    padding-left: 25px;
  }

  .navbar__toggle .bar {
    width: 25px;
    height: 3px;
    margin: 5px auto;
    transition: all 0.3s ease-in-out;
    background: #fff;
  }

  .navbar__item {
    width: 100%;
  }

  .navbar__links {
    text-align: center;
    padding: 2rem;
    width: 100%;
    display: table;
  }

  .navbar__btn {
    padding-bottom: 2rem;
  }

  .button {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 80%;
    height: 80px;
    margin: 0;
  }

  #mobile-menu {
    position: absolute;
    top: 20%;
    right: 5%;
    transform: translate(5%, 20%);
  }

  .navbar__toggle .bar {
    display: block;
    cursor: pointer;
  }

  #mobile-menu.is-active .bar:nth-child(2) {
    opacity: 0;
  }

  #mobile-menu.is-active .bar:nth-child(1) {
    transform: translateY(8px) rotate(45deg);
  }

  #mobile-menu.is-active .bar:nth-child(3) {
    transform: translateY(-8px) rotate(-45deg);
  }
}

/* Hero Section */
.hero {
  background: #000000;
  background: linear-gradient(to right, #161616, #000000);
  padding: 200px 0;
}

.hero__container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
  height: 30%;
  text-align: center;
  padding: 30px;
}

.hero__heading {
  font-size: 30px;
  margin-bottom: 24px;
  color: #fff;
}

.hero__heading span {
  background: #ee0979; /* fallback for old browsers */
  background: -webkit-linear-gradient(
    to right,
    #ff6a00,
    #ee0979
  ); /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(
    to right,
    #ff6a00,
    #ee0979
  ); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -mo-text-fill-color: transparent;
}

.highlight {
  border-bottom: 4px solid rgb(132, 0, 255);
}

@media screen and (max-width: 768px) {
  .hero__heading {
    font-size: 60px;
  }
}

/* About Section */
.main {
  background-color: #131313;
  padding: 10rem 0;
}

.main__container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  justify-content: center;
  margin: 0 auto;
  height: 90%;
  z-index: 1;
  width: 100%;
  max-width: 1300px;
  padding: 0 50px;
}

.main__content {
  color: #fff;
  width: 100%;
}

.main__content h1 {
  font-size: 2rem;
  background-color: #fe3b6f;
  background-image: linear-gradient(to top, #ff087b 0%, #ed1a52 100%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
  text-transform: uppercase;
  margin-bottom: 32px;
}

.main__content h2 {
  font-size: 4rem;
  background: #ff8177; /* fallback for old browsers */
  background: -webkit-linear-gradient(
    to right,
    #9114ff,
    #da22ff
  ); /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(
    to right,
    #8f0eff,
    #da22ff
  ); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}

.main__content p {
  margin-top: 1rem;
  font-size: 150%;
  font-weight: 700;
}

.main__btn {
  font-size: 1.8rem;
  background: #833ab4;
  background: -webkit-linear-gradient(to right, #fcb045, #fd1d1d, #833ab4);
  background: linear-gradient(to right, #fcb045, #fd1d1d, #833ab4);
  padding: 20px 60px;
  border: none;
  border-radius: 4px;
  margin-top: 2rem;
  cursor: pointer;
  position: relative;
  transition: all 0.35s;
  outline: none;
}

.main__btn a {
  position: relative;
  z-index: 2;
  color: #fff;
  text-decoration: none;
}

.main__btn:after {
  position: absolute;
  content: '';
  top: 0;
  left: 0;
  width: 0;
  height: 100%;
  background: #ff1ead;
  transition: all 0.35s;
  border-radius: 4px;
}

.main__btn:hover {
  color: #fff;
}

.main__btn:hover:after {
  width: 100%;
}

.main__img--container {
  text-align: center;
}

.main__img--card {
  margin: 10px;
  height: 500px;
  width: 500px;
  border-radius: 4px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  color: #fff;
  background-image: linear-gradient(to right, #00dbde 0%, #fc00ff 100%);
}

.fa-layer-group,
.fa-users {
  font-size: 14rem;
}

#card-2 {
  background: #ff512f;
  background: -webkit-linear-gradient(to right, #dd2476, #ff512f);
  background: linear-gradient(to right, #dd2476, #ff512f);
}

/* Mobile Responsive */
@media screen and (max-width: 1100px) {
  .main__container {
    display: grid;
    grid-template-columns: 1fr;
    align-items: center;
    justify-content: center;
    width: 100%;
    margin: 0 auto;
    height: 90%;
  }

  .main__img--container {
    display: flex;
    justify-content: center;
  }

  .main__img--card {
    height: 425px;
    width: 425px;
  }

  .main__content {
    text-align: center;
    margin-bottom: 4rem;
  }

  .main__content h1 {
    font-size: 2.5rem;
    margin-top: 2rem;
  }

  .main__content h2 {
    font-size: 3rem;
  }

  .main__content p {
    margin-top: 1rem;
    font-size: 1.5rem;
  }
}

@media screen and (max-width: 480px) {
  .main__img--card {
    width: 250px;
    height: 250px;
  }

  .fa-users,
  .fa-layer-group {
    font-size: 4rem;
  }

  .main__content h1 {
    font-size: 2rem;
    margin-top: 3rem;
  }
  .main__content h2 {
    font-size: 2rem;
  }

  .main__content p {
    margin-top: 2rem;
  }

  .main__btn {
    padding: 12px 36px;
    margin: 2.5rem 0;
  }
}

/* Services Section */
.services {
  background: #131313;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100%;
  padding: 10rem 0;
}

.services p{
  color: white;
  font-size: 150%;
}

.services h1 {
  background-color: #ff8177;
  background-image: linear-gradient(to right, #ff0844 0%, #f7673c 100%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
  margin-bottom: 5rem;
  font-size: 2.5rem;
}

.services h3 {
  background-color: #ff8177;
  background-image: linear-gradient(to right, #ff0844 0%, #f7673c 100%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
  margin-bottom: 1rem;
  font-size: 150%;
}

.services__wrapper {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-template-rows: 1fr;
}

.services__card {
  margin: 10px;
  height: 425px;
  width: 300px;
  border-radius: 4px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  color: #fff;
  background-image: linear-gradient(to right, #00dbde 0%, #fc00ff 100%);
  transition: 0.3s ease-in;
}

.services__card:nth-child(2) {
  background: #1fa2ff; /* fallback for old browsers */
  background: -webkit-linear-gradient(
    to right,
    #a6ffcb,
    #12d8fa,
    #1fa2ff
  ); /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(
    to right,
    #a6ffcb,
    #12d8fa,
    #1fa2ff
  ); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

.services__card:nth-child(3) {
  background-image: linear-gradient(
    -225deg,
    #231557 0%,
    #44107a 29%,
    #ff1361 67%,
    #fff800 100%
  );
}

.services__card h2 {
  text-align: center;
}

.services__card p {
  text-align: center;
  margin-top: 24px;
  font-size: 20px;
}

.services__btn {
  display: flex;
  justify-content: center;
  margin-top: 16px;
}

.services__card button {
  color: #fff;
  padding: 14px 24px;
  border: none;
  outline: none;
  border-radius: 4px;
  background: #131313;
  font-size: 1rem;
}

.services__card button:hover {
  cursor: pointer;
}

.services__card:hover {
  transform: scale(1.075);
  transition: 0.3s ease-in;
  cursor: pointer;
}

@media screen and (max-width: 1300px) {
  .services__wrapper {
    grid-template-columns: 1fr 1fr;
  }
}

@media screen and (max-width: 768px) {
  .services__wrapper {
    grid-template-columns: 1fr;
  }
}

/* Footer CSS */
.footer__container {
  background-color: #131313;
  padding: 5rem 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

#footer__logo {
  color: #fff;
  display: flex;
  align-items: center;
  cursor: pointer;
  text-decoration: none;
  font-size: 2rem;
}

.footer__links {
  width: 100%;
  max-width: 1000px;
  display: flex;
  justify-content: center;
}

.footer__link--wrapper {
  display: flex;
}

.footer__link--items {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  margin: 16px;
  text-align: left;
  width: 160px;
  box-sizing: border-box;
}

.footer__link--items h2 {
  margin-bottom: 16px;
  color: #fff;
}

.footer__link--items a {
  color: #fff;
  text-decoration: none;
  margin-bottom: 0.5rem;
  transition: 0.3 ease-out;
}

.footer__link--items a:hover {
  color: #e9e9e9;
  transition: 0.3 ease-out;
}

.social__icon--link {
  color: #fff;
  font-size: 24px;
}

.social__media {
  max-width: 1000px;
  width: 100%;
}

.social__media--wrap {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 90%;
  max-width: 1000px;
  margin: 40px auto 0 auto;
}

.social__icons {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 240px;
}

.website__rights {
  color: #fff;
}

@media screen and (max-width: 820px) {
  .footer__links {
    padding-top: 2rem;
  }

  #footer__logo {
    margin-bottom: 2rem;
  }

  .website__rights {
    margin-bottom: 2rem;
  }

  .footer__link--wrapper {
    flex-direction: column;
  }

  .social__media--wrap {
    flex-direction: column;
  }
}

@media screen and (max-width: 480px) {
  .footer__link--items {
    margin: 0;
    padding: 10px;
    width: 100%;
  }
}
</style>
