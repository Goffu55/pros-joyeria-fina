<template>
	<banners :loop="true" :autoplay="true" :items="1" :nav="false" :touchDrag="false" :dots="true" :freeDrag="false" :pullDrag="false" :autoplayHoverPause="false">
		<div class="item ed-grid s-grid-1 lg-grid-2" id="banner-1">
			<div class="s-y-2 lg-y-1 lg-x-1  s-main-center s-cross-center">
				<img src="../assets/img/bolsos_banner.png" alt="Bolso">
			</div>
			<div class="s-y-1 lg-x-2 lg-main-center lg-cross-center flex content">
				<h2 class="sentence1">Las carteras grandes nunca</h2>
				<h1 class="sentence2">pasan de moda</h1>
				<a class="button-style-1">VER MÁS<i class="fas fa-angle-double-right"></i></a>
			</div>
		</div>
		<div class="item ed-grid s-grid-1 lg-grid-2" id="banner-1">
			<div class="s-y-2 lg-y-1 lg-x-1  s-main-center s-cross-center">
				<img src="../assets/img/bolsos_banner.png" alt="Bolso">
			</div>
			<div class="s-y-1 lg-x-2 lg-main-center lg-cross-center flex content">
				<h2 class="sentence1">Las carteras grandes nunca</h2>
				<h1 class="sentence2">pasan de moda</h1>
				<a class="button-style-1">VER MÁS<i class="fas fa-angle-double-right"></i></a>
			</div>
		</div>
		<div class="item ed-grid s-grid-1 lg-grid-2" id="banner-1">
			<div class="s-y-2 lg-y-1 lg-x-1  s-main-center s-cross-center">
				<img src="../assets/img/bolsos_banner.png" alt="Bolso">
			</div>
			<div class="s-y-1 lg-x-2 lg-main-center lg-cross-center flex content">
				<h2 class="sentence1">Las carteras grandes nunca</h2>
				<h1 class="sentence2">pasan de moda</h1>
				<a class="button-style-1">VER MÁS<i class="fas fa-angle-double-right"></i></a>
			</div>
		</div>
		<div class="item ed-grid s-grid-1 lg-grid-2" id="banner-1">
			<div class="s-y-2 lg-y-1 lg-x-1  s-main-center s-cross-center">
				<img src="../assets/img/bolsos_banner.png" alt="Bolso">
			</div>
			<div class="s-y-1 lg-x-2 lg-main-center lg-cross-center flex content">
				<h2 class="sentence1">Las carteras grandes nunca</h2>
				<h1 class="sentence2">pasan de moda</h1>
				<a class="button-style-1">VER MÁS<i class="fas fa-angle-double-right"></i></a>
			</div>
		</div>
		<div class="item ed-grid s-grid-1 lg-grid-2" id="banner-1">
			<div class="s-y-2 lg-y-1 lg-x-1  s-main-center s-cross-center">
				<img src="../assets/img/bolsos_banner.png" alt="Bolso">
			</div>
			<div class="s-y-1 lg-x-2 lg-main-center lg-cross-center flex content">
				<h2 class="sentence1">Las carteras grandes nunca</h2>
				<h1 class="sentence2">pasan de moda</h1>
				<a class="button-style-1">VER MÁS<i class="fas fa-angle-double-right"></i></a>
			</div>
		</div>
	</banners>
</template>
<script>
	import banners from 'vue-owl-carousel'

	export default {
		components: { banners },
	};
</script>
<style>
.owl-dots {
	position: absolute;
	z-index: 100;
	top: 50%;
	right: 40px;
	transform: translateY(-50%);
	display: flex;
	flex-direction: column;
}
.owl-theme .owl-dots .owl-dot.active span, .owl-theme .owl-dots .owl-dot:hover span{
	background: #885d23;
	border-radius: 3px;
	
}
.owl-theme .owl-dots .owl-dot span, .owl-theme .owl-dots .owl-dot:hover span{
	background: rgba(191, 129, 49, 0.38);
	border-radius: 3px;
	
}
</style>	
