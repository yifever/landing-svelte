<script>
	import testimg1 from '$lib/assets/test1.jpeg';
	import testimg2 from '$lib/assets/test2.jpeg';
	import testimg3 from '$lib/assets/test3.jpeg';

	let testtext1 = 'AssLover3000 · 8:45 PM';
	let testtext2 = 'sandrone (e/λ) · 12:11 AM';
	let testtext3 = 'Ops Aeterna · 3:07 PM';
</script>

<div class=" bg-base-300 p-4 xl:p-10 rounded-lg m-4">
	<div class="max-w-lg mx-auto pb-10">
		<div class="text-3xl font-bold text-center my-5">Don't Just Trust Us</div>
		<div class="text-lg text-center my-5">Hear what people on X dot com are saying.</div>
	</div>

	<div class="flex flex-col lg:flex-row justify-center gap-5 xl:gap-10">
		<!-- first box -->
		<div class="flex flex-col justify-between bg-base-100 rounded-lg w-full shadow-lg">
			<div class="p-4 xl:p-10">
				<!-- MSG 1 -->
				<div class="chat chat-start">
					<div class="chat-image avatar">
						<div class="w-10 rounded-full">
							<img alt="avatar" src={testimg1} />
						</div>
					</div>
					<div class="chat-bubble">
						"For an alpha version, the intergration is surprisingly well-polished. I've encountered
						a few minor issues, but the overall experience has been positive. Excited to see where
						it goes from here!"
					</div>
					<div class="chat-footer opacity-50">
						{testtext1}
					</div>
				</div>
			</div>
		</div>
		<!-- second box -->
		<div class="flex flex-col justify-between bg-base-100 rounded-lg w-full shadow-lg">
			<div class="p-4 xl:p-10">
				<!-- MSG 1 -->
				<div class="chat chat-start">
					<div class="chat-image avatar">
						<div class="w-10 rounded-full">
							<img alt="avatar" src={testimg2} />
						</div>
					</div>
					<div class="chat-bubble">
						"Never thought I'd be comfortable with the idea of giving an AI my credit card, but this
						app showcased the capabilities and ethics of modern tech. A real eye-opener! Would give
						AI my credit card again."
					</div>
					<div class="chat-footer opacity-50">{testtext2}</div>
				</div>
			</div>
		</div>
		<!-- third box -->
		<div class="flex flex-col justify-between bg-base-100 rounded-lg w-full shadow-lg">
			<div class="p-4 xl:p-10">
				<!-- MSG 1 -->
				<div class="chat chat-start">
					<div class="chat-image avatar">
						<div class="w-10 rounded-full">
							<img alt="avatar" src={testimg3} />
						</div>
					</div>
					<div class="chat-bubble">
						"Skeptical at first, but GCYCC turned out to be an innovative and safe experience. I've
						learned so much about the technology and potential of AI and bought my friend a nice
						gift. Highly recommend!"
					</div>
					<div class="chat-footer opacity-50">{testtext3}</div>
				</div>
			</div>
		</div>

		<!-- old template
		<div class="flex flex-col justify-between bg-base-100 rounded-lg w-full shadow-lg">
			<div class="p-4 xl:p-10">
				<div class="chat chat-start">
					<div class="chat-image avatar">
						<div class="w-10 rounded-full">
							<img
								alt="avatar"
								src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
							/>
						</div>
					</div>
					<div class="chat-header">
						Obi-Wan Kenobi
						<time class="text-xs opacity-50">12:45</time>
					</div>
					<div class="chat-bubble">Anakin</div>
					<div class="chat-footer opacity-50">Delivered</div>
				</div>

				<div class="chat chat-start">
					<div class="chat-image avatar">
						<div class="w-10 rounded-full">
							<img
								alt="avatar"
								src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
							/>
						</div>
					</div>
					<div class="chat-header">
						Obi-Wan Kenobi
						<time class="text-xs opacity-50">12:45</time>
					</div>
					<div class="chat-bubble">You were the Chosen One!</div>
					<div class="chat-footer opacity-50">Delivered</div>
				</div>

				<div class="chat chat-end">
					<div class="chat-image avatar">
						<div class="w-10 rounded-full">
							<img
								alt="avatar"
								src="https://images.unsplash.com/photo-1517365830460-955ce3ccd263?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
							/>
						</div>
					</div>
					<div class="chat-header">
						Anakin
						<time class="text-xs opacity-50">12:46</time>
					</div>
					<div class="chat-bubble bg-primary">I hate you!</div>
					<div class="chat-footer opacity-50">Seen at 12:46</div>
				</div>
			</div>
		</div>
-->
	</div>
</div>
