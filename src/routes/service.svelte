<script lang="ts">


	const features = [
		{
			title: 'Design',
			icon: 'upload',
			description:
				'Wordpress, Photoshop, Canva'
		},
		// {
		// 	title: 'Stream On-Demand',
		// 	icon: 'record',
		// 	description: 'Showcase your content in a beautiful on-demand video catalog.'
		// },
		// {
		// 	title: 'Stream live',
		// 	icon: 'stream',
		// 	description: 'Schedule events in advance & build excitement with a countdown overlay.'
		// },
		// {
		// 	title: 'Monetization',
		// 	icon: 'monetization',
		// 	description: 'Offer subscriptions or one-time purchases. Accept credit cards & PayPal.'
		// },
		{
			title: 'Analytics',
			icon: 'stream',
			description: 'Data science'
		},
		{
			title: 'Developer',
			icon: 'device',
			description: 'Html, Css, JavaScript, React, Flutter'
		}
	]
</script>

<section class="py-20 bg-white text-black">
	<div class="max-w-screen-lg mx-auto">
		<div class="flex flex-col justify-center text-center">
			<div class="flex flex-col space-y-3">
				<h2 class="text-4xl font-bold font-heading">Services</h2>
				<p>Below are the services i provide</p>
			</div>
			
		</div>
		<div class="grid grid-cols-3 gap-12 mt-20">
			{#each features as feature}
				<div
					class="flex flex-col p-4 space-y-3 hover:shadow-2xl transition duration-300 cursor-pointer"
				>
					<div class="flex space-x-3">
						<img
							src={`/icons/${feature.icon}.svg`}
							class="transform transition duration-300 hover:rotate-12"
							alt={feature.title}
						/>
						<h5 class="font-bold font-heading">{feature.title}</h5>
					</div>
					<p>{feature.description}</p>
				</div>
			{/each}
		</div>
	</div>
</section>