<template>
	<div class="banner">
		<div class="content">
			<h1>Hi. I'm <span>Bill Justin</span>.<br>I create professional websites.</h1>
			<div class="links">
				<a href="#" data-text="about">about me</a>
				<a href="#" data-text="contact">contact</a>
				<a href="#" data-text="portfolio">portfolio</a>
			</div>
		</div>
	</div>
</template>

<script>
import VanillaTilt from 'vanilla-tilt'
export default {
	name: 'Home',
	data() 
	{
		return {

		}
	},

	mounted()
	{
		VanillaTilt.init(document.querySelector(".content"), {
			max: 25,
			speed: 1000,
			// reverse: true
		});
	}
}
</script>
<style>
	body {
		overflow-y: hidden; 
	}
</style>