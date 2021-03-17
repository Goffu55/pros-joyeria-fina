<template>
	<div class="ed-grid s-gap-1 s-grid-2 lg-gap-4 lg-grid-4">
		<div v-for="product in products" :key="product.id" class="container-product flex">
			<img class="img-product" :src="product.img" alt="producto">
			<h3 class="title-product">{{ product.title }}</h3>
			<p class="description-product">{{ product.description }}<span>{{ product.price }}</span></p>
			<a :href="product.link" class="button-product">VER MÁS</a>
		</div>
	</div>
</template>
<script>

export default{
	name: "products",
	data () {
		return {
			products: [
			{	
				"id" : "1",
				"img" : "http://joyeria-fina.test/img/icono_pagos.png",
				"title" : "Collar",
				"description" : "Lorem Ipsum",
				"price" : "10000",
				"link" : "http://joyeria-fina.test/collar"
			},
			{
				"id" : "2",
				"img" : "http://joyeria-fina.test/img/icono_productos.png",
				"title" : "Anillo",
				"description" : "Lorem Ipsum",
				"price" : "10000",
				"link" : "http://joyeria-fina.test/anillo"
			},
			{
				"id" : "2",
				"img" : "http://joyeria-fina.test/img/icono_productos.png",
				"title" : "Anillo",
				"description" : "Lorem Ipsum",
				"price" : "10000",
				"link" : "http://joyeria-fina.test/anillo"
			},
			{
				"id" : "2",
				"img" : "http://joyeria-fina.test/img/icono_productos.png",
				"title" : "Anillo",
				"description" : "Lorem Ipsum",
				"price" : "10000",
				"link" : "http://joyeria-fina.test/anillo"
			},
			{
				"id" : "2",
				"img" : "http://joyeria-fina.test/img/icono_productos.png",
				"title" : "Anillo",
				"description" : "Lorem Ipsum",
				"price" : "10000",
				"link" : "http://joyeria-fina.test/anillo"
			},
			{
				"id" : "2",
				"img" : "http://joyeria-fina.test/img/icono_productos.png",
				"title" : "Anillo",
				"description" : "Lorem Ipsum",
				"price" : "10000",
				"link" : "http://joyeria-fina.test/anillo"
			},
			{
				"id" : "2",
				"img" : "http://joyeria-fina.test/img/icono_productos.png",
				"title" : "Anillo",
				"description" : "Lorem Ipsum",
				"price" : "10000",
				"link" : "http://joyeria-fina.test/anillo"
			},
			{
				"id" : "3",
				"img" : "http://joyeria-fina.test/img/iconos_Envios.png",
				"title" : "Pulsera",
				"description" : "Lorem Ipsum",
				"price" : "10000",
				"link" : "http://joyeria-fina.test/pulsera"
			}	
			]
		}
	}
};
</script>