<template>
	<section2Carousel :loop="true" :autoplay="true" :items="1" :nav="false" :dots="false" :touchDrag="true" :autoplayHoverPause="false">
		<div class="lg-x-2 ed-grid lg-grid-2 lg-gap-1">
			<div class="img-character flex">
				<img src="../assets/img/icono_pagos.png" alt="img-pagos">
			</div>
			<div>
				<h1 class="title-style-1" align="lg-cross-centerter">Pagos</h1>
				<h2 class="title-style-2" align="center">Lorem Ipsum</h2>
			</div>
		</div>
		<div class="lg-x-3 ed-grid lg-grid-2 lg-gap-1">
			<div class="img-character flex">
				<img src="../assets/img/iconos_Envios.png" alt="img-envios">  
			</div>
			<div>
				<h1 class="title-style-1" align="center">Envios</h1>
				<h2 class="title-style-2" align="center">Lorem Ipsum</h2>
			</div>
		</div>
		<div class="lg-x-4 ed-grid lg-grid-2 lg-gap-1">
			<div class="img-character flex" >
				<img src="../assets/img/icono_productos.png" alt="img-productos">
			</div>
			<div>
				<h1 class="title-style-1" align="center">Productos</h1>
				<h2 class="title-style-2" align="center">Lorem Ipsum</h2>
			</div>
		</div>
	</section2Carousel>
</template>
<script>
	import section2Carousel from 'vue-owl-carousel'

	export default {
		components: { section2Carousel },
	};
</script>