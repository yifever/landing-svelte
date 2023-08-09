<script lang="ts">
	import Carousel from '$lib/components/Carousel.svelte';
	import Chat from '$lib/components/Chat.svelte';
	import Hero from '$lib/components/Hero.svelte';
	import Mobile from '$lib/components/Mobile.svelte';
	import Stats from '$lib/components/Stats.svelte';
	import HeroCards from '$lib/components/HeroCards.svelte';
	import Links from '$lib/components/Links.svelte';
	import Countdown from '$lib/components/Countdown.svelte';
	import Drawer from '$lib/components/Drawer.svelte';
	import Card from '$lib/components/Card.svelte';
	import Gif from '$lib/components/Gif.svelte';
	import Testimonials from '$lib/components/Testimonials.svelte';
</script>

<div>
	<div class="">
		<div class="">
			<Hero />
		</div>
		<!-- <div class="lg:container mx-auto">
			<Carousel />
		</div>
-->
	</div>
	<div class="container mx-auto">
		<Gif />
		<div class="my-10">
			<HeroCards />
		</div>

		<!-- <Stats /> -->
		<Testimonials />
		<!--
		<div class="my-10">
			<Mobile />
		</div>
-->
	</div>
</div>
