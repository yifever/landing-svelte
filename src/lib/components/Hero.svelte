<script lang="ts">
	let email: string = '';
	let message: string = '';

	function signUpForWaitlist() {
		if (!validateEmail(email)) {
			message = 'Please enter a valid email.';
			return;
		}

		message = 'Thanks for signing up! But even this site is just a demo!';
		email = ''; // clear the input
	}

	function validateEmail(email: string) {
		var pattern = new RegExp('[a-z0-9]+@[a-z]+.[a-z]{2,3}');
		return email.match(pattern);
	}
</script>

<div
	class="hero h-[100vh] lg:h-[45rem] shadow-lg"
	style="background-image: url('https://images.unsplash.com/photo-1644325349124-d1756b79dd42?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2675&q=80');"
>
	<div class="hero-overlay bg-opacity-70" />
	<div class="hero-content text-neutral-content">
		<div class="z-60 drop-shadow-lg text-center">
			<div class="mb-5 text-8xl font-semibold">MeCube</div>
			<div class="mb-5 max-w-sm">Never do a Captcha again</div>
			<div class="flex gap-4 justify-center">
				<input
					type="text"
					class="block border border-grey-light w-full p-3 rounded mb-4"
					name="email"
					bind:value={email}
					placeholder="Email"
				/>
			</div>
			<div class="flex gap-4 justify-center">
				<button
					class="btn btn-primary transition-color duration-300 text-lg"
					on:click={signUpForWaitlist}
				>
					Sign Up for a Free Demo
				</button>
			</div>
			<div class="flex gap-4 justify-center">
				<span>
					<p>{message}</p>
				</span>
			</div>
		</div>
	</div>
</div>
