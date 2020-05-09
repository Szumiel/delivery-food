<!DOCTYPE html>
<html lang="ru">

<head>
    <meta charset="UTF-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Delivery Food — доставка еды на дом</title>
    <link href="https://fonts.googleapis.com/css?family=Roboto:400,700&display=swap&subset=cyrillic" rel="stylesheet"/>
    <link rel="stylesheet" href="css/normalize.css"/>
    <link rel="stylesheet" href="css/style.css"/>
    <link rel="stylesheet" href="https://unpkg.com/swiper/css/swiper.min.css">
</head>

<body>
	<div class="container">
		<header class="header">
			<a class="logo">
				<img src="img/icon/logo.svg" alt="Logo"/>
			</a>
			<label class="address">
				<input type="text" class="input input-address" placeholder="Адрес доставки"/>
			</label>
			<div class="buttons">
				<span class="user-name"></span>
				<button class="button button-primary button-auth">
					<span class="button-auth-svg"></span>
					<span class="button-text">Войти</span>
				</button>
				<button class="button button-cart" id="cart-button">
					<span class="button-cart-svg"></span>
					<span class="button-text">Корзина</span>
				</button>
				<button class="button button-primary button-out">
					<span class="button-text">Выйти</span>
					<span class="button-out-svg"></span>
				</button>
			</div>
		</header>
	</div>
	<!-- /.container  -->

	<main class="main container">
		<div class="container">
			<div class="container-promo swiper-container">
				<section class="swiper-wrapper">
					<section class="swiper-slide promo pizza">
						<h1 class="promo-title">Онлайн-сервис <br/>доставки еды на дом</h1>
						<p class="promo-text">
							Блюда из любимого ресторана привезет курьер в перчатках, маске и с антисептиком
						</p>
					</section>
					<section class="swiper-slide promo kebab">
						<h1 class="promo-title">Шашлыки на майские <br> со скидкой 35%</h1>
						<p class="promo-text">
							Закажите шашлыки в любом ресторане до 10 мая и получите скидку по промокоду OMAGAD
						</p>
					</section>
					<section class="swiper-slide promo vegetables">
						<h1 class="promo-title">Скидка 20% на всю еду <br> по промокоду LOVE.JS</h1>
						<p class="promo-text">
							Блюдо из ресторана привезут вместе с двумя подарочными книгами по фронтенду
						</p>
					</section>
					<section class="swiper-slide promo sushi">
						<h1 class="promo-title">Сеты со скидкой до 30% <br> в ресторанах</h1>
						<p class="promo-text">
							Скидки на сеты до 30 мая по промокоду DADADA
						</p>
					</section>
				</section>
			</div>
			<section class="restaurants">
				<div class="section-heading">
					<h2 class="section-title">Рестораны</h2>
					<label class="search">
						<input type="text" class="input input-search" placeholder="Поиск блюд и ресторанов"/>
					</label>
				</div>
				<div class="cards cards-restaurants">
					
				</div>
				<!-- /.cards -->
			</section>
			<section class="menu hide">
				<div class="section-heading">
					<h2 class="section-title restaurant-title">Пицца Плюс</h2>
					<div class="card-info">
						<div class="rating">
							4.5
						</div>
						<div class="price">От 900 ₽</div>
						<div class="category">Пицца</div>
					</div>
					<!-- /.card-info -->
				</div>
				<div class="cards cards-menu">
					
				</div>
				<!-- /.cards -->
			</section>
		</div>
		<!-- /.container -->
	</main>

	<footer class="footer">
		<div class="container">
			<div class="footer-block">
				<img src="img/icon/logo.svg" alt="logo" class="logo footer-logo"/>
				<nav class="footer-nav">
					<a href="#" class="footer-link">Ресторанам </a>
					<a href="#" class="footer-link">Курьерам</a>
					<a href="#" class="footer-link">Пресс-центр</a>
					<a href="#" class="footer-link">Контакты</a>
				</nav>
				<div class="social-links">
					<a href="#" class="social-link"><img src="img/social/instagram.svg" alt="instagram"/></a>
					<a href="#" class="social-link"><img src="img/social/fb.svg" alt="facebook"/></a>
					<a href="#" class="social-link"><img src="img/social/vk.svg" alt="vk"/></a>
				</div>
				<!-- /.social-links -->
			</div>
			<!-- /.footer-block -->
		</div>
	</footer>

	<div class="modal modal-cart">
		<div class="modal-dialog">
			<div class="modal-header">
				<h3 class="modal-title">Корзина</h3>
				<button class="close">&times;</button>
			</div>
			<!-- /.modal-header -->
			<div class="modal-body">
				<div class="food-row">
					<span class="food-name">Ролл угорь стандарт</span>
					<strong class="food-price">250 ₽</strong>
					<div class="food-counter">
						<button class="counter-button">-</button>
						<span class="counter">1</span>
						<button class="counter-button">+</button>
					</div>
				</div>
				<!-- /.foods-row -->
				<div class="food-row">
					<span class="food-name">Ролл угорь стандарт</span>
					<strong class="food-price">250 ₽</strong>
					<div class="food-counter">
						<button class="counter-button">-</button>
						<span class="counter">1</span>
						<button class="counter-button">+</button>
					</div>
				</div>
				<!-- /.foods-row -->
				<div class="food-row">
					<span class="food-name">Ролл угорь стандарт</span>
					<strong class="food-price">250 ₽</strong>
					<div class="food-counter">
						<button class="counter-button">-</button>
						<span class="counter">1</span>
						<button class="counter-button">+</button>
					</div>
				</div>
				<!-- /.foods-row -->
				<div class="food-row">
					<span class="food-name">Ролл угорь стандарт</span>
					<strong class="food-price">250 ₽</strong>
					<div class="food-counter">
						<button class="counter-button">-</button>
						<span class="counter">1</span>
						<button class="counter-button">+</button>
					</div>
				</div>
				<!-- /.foods-row -->
			</div>
			<!-- /.modal-body -->
			<div class="modal-footer">
				<span class="modal-pricetag">1250 ₽</span>
				<div class="footer-buttons">
					<button class="button button-primary">Оформить заказ</button>
					<button class="button clear-cart">Отмена</button>
				</div>
			</div>
			<!-- /.modal-footer -->
		</div>
		<!-- /.modal-dialog -->
	</div>

	<div class="modal-auth">
		<div class="modal-dialog modal-dialog-auth">
			<button class="close-auth">&times;</button>
			<form id="logInForm">
				<fieldset class="modal-body">
					<legend class="modal-title">Авторизация</legend>
					<label class="label-auth">
						<span>Логин</span>
						<input id="login" type="text">
					</label>
					<label class="label-auth">
						<span>Пароль</span>
						<input id="password" type="password">
					</label>
				</fieldset>
				<!-- /.modal-body -->
				<div class="modal-footer">
					<div class="footer-buttons">
						<button class="button button-primary button-login" type="submit">Войти</button>
					</div>
				</div>
			</form>
			<!-- /.modal-footer -->
		</div>
		<!-- /.modal-dialog -->
	</div>
	<script src="https://unpkg.com/swiper/js/swiper.min.js"></script>
	<script src="js/main.js"></script>
</body>

</html>
