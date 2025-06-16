<script>
	// You will need to replace these with actual image paths
	const logos = [
		{ src: '/stats/1.png', alt: 'Tech Marvels' },
		{ src: '/stats/2.png', alt: 'Horizon' },
		{ src: '/stats/3.png', alt: 'Edistys' }
	];
</script>

<div class="flex flex-col items-center py-8 text-center bg-white">
	<h2 class="text-2xl font-bold text-gray-800 mb-12 max-w-3xl">
		Dail Leads <span class="text-purple-700">Powers 10M+ ROI</span>-positive Customer Interactions
		per Month
	</h2>
	<div class="flex justify-center items-center flex-wrap gap-16">
		{#each logos as logo (logo.src)}
			<img src={logo.src} alt={logo.alt} class="h-12 filter grayscale opacity-70" />
		{/each}
	</div>
</div>
