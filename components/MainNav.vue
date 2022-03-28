<template>
	<div class="bg-image-main ">
		<div class="container pt-2">
			<div class="mb-3 d-flex justify-content-between">
				<div class=" align-self-center">
					<a href="" class="logo">
						<img src="../assets/img/logo_main.jpg" alt="">
					</a>
				</div>
				<div class="main_nav font-weight-bold d-flex justify-content-between  align-self-center">
					<a class="nav-item">
						Главная
					</a>
					<a class="nav-item">
						О нас
					</a>
					<a class="nav-item">
						Команда
					</a>
					<a class="nav-item">
						THS
					</a>
					<a class="dropdown-toggle nav-item" href="#" role="button" id="dropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
						Ice Service
					</a>
					<div class="dropdown-menu" aria-labelledby="dropdownMenuLink">
						<a class="dropdown-item" href="#">Action</a>
						<a class="dropdown-item" href="#">Another action</a>
						<a class="dropdown-item" href="#">Something else here</a>
						<div class="dropdown-divider"></div>
						<a class="dropdown-item" href="#">Separated link</a>
					</div>
				</div>
				<div class="contact-phone align-self-center ">
					<a href="tel:+77755911120" class="text-white phone-text">
						+7 (775) 591 11 20
					</a>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {

}
</script>

<style scoped>

h6 {
	margin-bottom: 0;
}

.brd-radius {
	border-radius: 9px;
}

.main_nav {
	border-radius: 9px;
	padding: 9px;
}

.nav-item {
	color: #fff;
	font-weight: 350;
	margin-right: 20px;
}

.nav-item:hover {
	color: #00fff1;
}

.logo img {
	width: 100%;
	height: 75px;
}

.contact-phone {
	border-radius: 9px;
	padding: 9px;
	width: 75px;
	position: relative;
}

.contact-phone a {
	position: absolute;
	left: -75px;
	top: 0;
}

.phone-text {
	width: 150px;
}

</style>
