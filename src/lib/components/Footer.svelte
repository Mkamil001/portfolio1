<footer class="py-20 bg-gray-100 px-10">
	<div class="max-w-screen-xl mx-auto flex justify-between space-x-14">
		<div class="flex flex-col space-y-6 w-1/4">
			<!-- <img src="/images/screeno-footer.svg" width={99} height={13} alt="Screeno Logo" /> -->
			<p></p>
			<!-- <div class="flex space-x-4">
				<img src="/icons/facebook.svg" alt="Facebook" />
				<img src="/icons/instagram.svg" alt="Instagram" />
			</div> -->
		</div>
		<div class="flex flex-col space-y-6 w-1/4 items-right">
			<h6 class="font-semibold font-heading">Contact Info</h6>
			<div class="flex items-start space-x-2">
				<img src="/icons/location.svg" alt="Location Icon" />
				<p>Ashongman Estate F-line</p>
			</div>
			<div class="flex items-center space-x-2">
				<img src="/icons/phone.svg" alt="Phone Icon" />
				<p>(+233)55 718 9826</p>
			</div>
			<div class="flex items-center space-x-2">
				<img src="/icons/email-blue.svg" alt="Email Icon" />
				<p>mkamil001@st.ug.edu.gh</p>
			</div>
		</div>
		<div class="flex flex-col space-y-6 w-1/2 items-left flex-between">
			<h6 class="font-heading font-semibold">Get in touch</h6>
			<form class="flex flex-col space-y-6">
				<input type="text" placeholder="Your name" />
				<input type="email" placeholder="Your email" />
				<textarea placeholder="Your message" rows={5} />
				<div>
					<button class="primary font-heading font-semibold px-8">Send</button>
				</div>
			</form>
		</div>
	</div>
</footer>
<div class="border-t-[1px] border-neutral-300 text-center py-4">
	<p>©2022 Designed by Marwan, All rights reserved</p>
</div>

<style lang="postcss">
	input,
	textarea {
		@apply text-neutral-700 py-3 px-4 outline-none rounded-xl border-[1px] border-white focus:border-primary transition duration-300;
	}
</style>