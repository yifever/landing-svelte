<script>
	import MyGif from '$lib/assets/solvecaptcha.gif';
</script>

<div class="p-4 xl:p-10 bg-base-300 my-10 rounded-lg">
	<div class="max-w-lg mx-auto pb-10">
		<div class="text-3xl font-bold text-center my-5">Your Captcha is Already Out of Date</div>
		<div class="text-lg text-center my-5">
			Malicious attackers are using AI software to crack your Captcha millions of times every day.
		</div>
	</div>

	<div class="flex flex-col items-center justify-center">
		<img src={MyGif} alt="testimg" />
	</div>
</div>
