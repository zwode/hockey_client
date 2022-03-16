<template>
	<div>
		<div class="mb-3 d-flex justify-content-between">
			<div class="logo">
				<img src="../assets/img/logo.png" alt="">
			</div>
			<div class="contact-phone align-self-center bg-brand">
				<a href="tel:+77019563020" class="text-white">
					+7 (701) 956 30 20
				</a>
			</div>
		</div>
		<div class="main_nav bg-brand d-flex justify-content-between">
			<a class="nav-item">
				Главная
			</a>
			<a class="nav-item">
				О нас
			</a>
			<a class="nav-item">
				Хокей
			</a>
			<a class="nav-item">
				Расписание
			</a>
			<a class="nav-item">
				Тренеры
			</a>
			<a class="nav-item">
				Контакты
			</a>
		</div>

	</div>
</template>

<script>
export default {

}
</script>

<style scoped>

.main_nav {
	border-radius: 9px;
	padding: 9px;
}

.nav-item {
	color: #fff;
	font-weight: 350;
}

.nav-item:hover {
	color: #00fff1;
}

.logo img {
	width: 100%;
	height: 50px;
}

.contact-phone {
	border-radius: 9px;
	padding: 9px;
}

</style>
