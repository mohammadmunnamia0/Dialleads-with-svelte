<script>
	import Icon from '@iconify/svelte';
	import HeroBanner from './HeroBanner.svelte';
</script>

<main class="min-h-screen text-white flex flex-col items-center justify-center px-4">
	<section class="w-full max-w-7xl mx-auto">
		<section class="text-center max-w-3xl mx-auto space-y-6">
			<div
				class="inline-flex items-center gap-2 px-4 py-2 rounded-full border border-purple-500 text-sm text-white bg-[#1a122f] shadow-md"
			>
				<Icon icon="mdi:check-circle" width="18" height="18" class="text-purple-400" />
				<span>AI can now make & take calls on your behalf!</span>
			</div>

			<h1 class="text-4xl sm:text-5xl md:text-6xl font-extrabold leading-tight">
				Effortless Human-Like<br />
				<span class="text-purple-400">AI Phone Calls</span>
			</h1>
			<p class="text-lg text-gray-300">
				Boost conversions with AI-powered voice agents and<br />
				never miss a lead again.
			</p>
			<div>
				<div>
					<button
						class="mt-4 inline-flex items-center gap-2 px-6 py-3 bg-gradient-to-r from-purple-600 to-purple-400 px-5 py-2 rounded-xl text-white text-sm font-medium border-2 border-purple-400 hover:opacity-90 transition cursor-pointer"
					>
						<Icon icon="mdi:mail" width="18" height="18" />
						Contact Sales
					</button>
				</div>
			</div>
		</section>
		<section class="mt-28">
			<HeroBanner />
		</section>
	</section>
</main>
