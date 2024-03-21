<template>
   <main>
    <div id="billboard" class="jarallax" data-aos="fade">
	<div class="banner-content">
		<div class="banner-header">
			<span>Hi! everyone</span>
			<h2 class="light">Aleksey Gryzlov<br/> .Net developer</h2>
			<p>Make monolyte and microservice system, greatful Wpf design, database engineering.</p>
		</div>
	</div>

	<img :src="banner" class="jarallax-img">
</div><!--billboard-->
   </main>
</template>

<script setup>
import banner from "../assets/main-banner.jpg"
</script>