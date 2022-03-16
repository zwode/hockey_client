<template>
	<div class="mt-5">
		<h2>
			Что у нас есть
		</h2>
		<b-card no-body>
			<b-tabs card>
				<b-tab title="Tab 1" active>
					<div class="d-flex">
						<div class="w-50 p-2">
							<h6>
								УНИКАЛЬНОЕ ХОЛОДИЛЬНОЕ ОБОРУДОВАНИЕ ДЛЯ КАТКОВ.
							</h6>
							<p>
								Важнейший элемент ледового катка - искусственный лед. Он создается с помощью специального холодильного оборудования.<br><br>

								Низкотемпературные моноблочные чиллеры (chiller (англ.) - холодильник) серии GBAV и GSA разработаны для катков разного размера с мощностью охлаждения от 20 до 800 кВт. Они оснащены энергосберегающими полу-герметическими компрессорами, низкошумовыми вентиляторами и таймерами для автоматического включения/выключения по заданным суточным режимам. Защита панели управления по стандартам IP55.
								<br><br>
								Купите чиллеры Industrial Frigo - это высокое качество, надежная сборка только из европейских комплектующих.<br><br>

								Цена на чиллер от 30000€
							</p>
						</div>
						<div class="w-50">
							<b-carousel
								id="carousel-1"
								v-model="slide"
								:interval="4000"
								controls
								indicators
								background="#ababab"
								img-width="100%"
								img-height="260"
								style="text-shadow: 1px 1px 2px #333;"
								@sliding-start="onSlideStart"
								@sliding-end="onSlideEnd"
							>
								<!-- Text slides with image -->
								<b-carousel-slide
									caption="First slide"
									text="Nulla vitae elit libero, a pharetra augue mollis interdum."
									img-src="https://picsum.photos/1024/480/?image=52"
								></b-carousel-slide>

								<!-- Slides with custom text -->
								<b-carousel-slide img-src="https://picsum.photos/1024/480/?image=54">
									<h1>Hello world!</h1>
								</b-carousel-slide>

								<!-- Slides with image only -->
								<b-carousel-slide img-src="https://picsum.photos/1024/480/?image=58"></b-carousel-slide>

								<!-- Slides with img slot -->
								<!-- Note the classes .d-block and .img-fluid to prevent browser default image alignment -->
								<b-carousel-slide>
									<template #img>
										<img
											class="d-block img-fluid w-100"
											width="1024"
											height="480"
											src="https://picsum.photos/1024/480/?image=55"
											alt="image slot"
										>
									</template>
								</b-carousel-slide>

								<!-- Slide with blank fluid image to maintain slide aspect ratio -->
								<b-carousel-slide caption="Blank Image" img-blank img-alt="Blank image">
									<p>
										Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse eros felis, tincidunt
										a tincidunt eget, convallis vel est. Ut pellentesque ut lacus vel interdum.
									</p>
								</b-carousel-slide>
							</b-carousel>
						</div>
					</div>
				</b-tab>
				<b-tab title="Tab 2">
					<b-tab title="Tab2">
						<div class="d-flex">
							<div class="w-50 p-2">
								<h6>
									УНИКАЛЬНОЕ ХОЛОДИЛЬНОЕ ОБОРУДОВАНИЕ ДЛЯ КАТКОВ.
								</h6>
								<p>
									Важнейший элемент ледового катка - искусственный лед. Он создается с помощью специального холодильного оборудования.<br><br>

									Низкотемпературные моноблочные чиллеры (chiller (англ.) - холодильник) серии GBAV и GSA разработаны для катков разного размера с мощностью охлаждения от 20 до 800 кВт. Они оснащены энергосберегающими полу-герметическими компрессорами, низкошумовыми вентиляторами и таймерами для автоматического включения/выключения по заданным суточным режимам. Защита панели управления по стандартам IP55.
									<br><br>
									Купите чиллеры Industrial Frigo - это высокое качество, надежная сборка только из европейских комплектующих.<br><br>

									Цена на чиллер от 30000€
								</p>
							</div>
							<div class="w-50">
								<b-carousel
									id="carousel-1"
									v-model="slide"
									:interval="4000"
									controls
									indicators
									background="#ababab"
									img-width="100%"
									img-height="260"
									style="text-shadow: 1px 1px 2px #333;"
									@sliding-start="onSlideStart"
									@sliding-end="onSlideEnd"
								>
									<!-- Text slides with image -->
									<b-carousel-slide
										caption="First slide"
										text="Nulla vitae elit libero, a pharetra augue mollis interdum."
										img-src="https://picsum.photos/1024/480/?image=52"
									></b-carousel-slide>

									<!-- Slides with custom text -->
									<b-carousel-slide img-src="https://picsum.photos/1024/480/?image=54">
										<h1>Hello world!</h1>
									</b-carousel-slide>

									<!-- Slides with image only -->
									<b-carousel-slide img-src="https://picsum.photos/1024/480/?image=58"></b-carousel-slide>

									<!-- Slides with img slot -->
									<!-- Note the classes .d-block and .img-fluid to prevent browser default image alignment -->
									<b-carousel-slide>
										<template #img>
											<img
												class="d-block img-fluid w-100"
												width="1024"
												height="480"
												src="https://picsum.photos/1024/480/?image=55"
												alt="image slot"
											>
										</template>
									</b-carousel-slide>

									<!-- Slide with blank fluid image to maintain slide aspect ratio -->
									<b-carousel-slide caption="Blank Image" img-blank img-alt="Blank image">
										<p>
											Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse eros felis, tincidunt
											a tincidunt eget, convallis vel est. Ut pellentesque ut lacus vel interdum.
										</p>
									</b-carousel-slide>
								</b-carousel>
							</div>
						</div>
					</b-tab>
				</b-tab>
			</b-tabs>
		</b-card>
	</div>
</template>

<script>
export default {

}
</script>

<style>
	.w-50 .img-fluid {
		max-height: 300px!important;
	}
</style>
