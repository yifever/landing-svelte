<script>
	import Hero from './Hero.svelte';
</script>

<div class="p-4 xl:p-10 bg-base-300 my-10 rounded-lg">
	<div class="max-w-lg mx-auto pb-10">
		<div class="text-3xl font-bold text-center my-5">Mobile App</div>
		<div class="text-lg text-center my-5">Verify all of your accounts within a single app.</div>
	</div>

	<div class="flex justify-center">
		<div class="mockup-phone shadow-xl">
			<div class="camera" />
			<div class="display">
				<div class="artboard artboard-demo phone-1">
					<Hero />
				</div>
			</div>
		</div>
	</div>
</div>
