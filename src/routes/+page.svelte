<!-- Script Imports -->
<script>
	import Hero from '../components/homepage/Hero.svelte';
	import Navbar from '../components/homepage/Navbar.svelte';
</script>

<!-- Body Main Components -->
<main>
	<Navbar />
	<section class="bg-[#0a021a] mx-2 ">
		<Hero />
	</section>
</main>

<!-- Style -->
<style lang="postcss">
	@reference "tailwindcss";
	:global(html) {
		background-color: theme(--color-gray-100);
	}
</style>
