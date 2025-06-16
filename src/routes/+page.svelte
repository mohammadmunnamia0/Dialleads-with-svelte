<!-- Script Imports -->
<script>
	import Features from '../components/homepage/Features/Features.svelte';
	import Hero from '../components/homepage/Hero.svelte';
	import Navbar from '../components/homepage/Navbar.svelte';
	import StatsHighlight from '../components/homepage/StatsHighlight.svelte';
</script>

<!-- Body Main Components -->
<main>
	<Navbar />
	<section class="bg-[#0a021a] mx-3 rounded-bl-xl rounded-br-xl ">
		<Hero />
	</section>
    <StatsHighlight/>
    <Features/>
</main>

<!-- Style -->
<style lang="postcss">
	@reference "tailwindcss";
	:global(html) {
		background-color: theme(--color-gray-100);
	}
</style>
