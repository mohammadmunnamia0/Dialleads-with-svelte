<!-- Script Imports -->
<script>
	import Hero from "../components/homepage/Hero.svelte";
	import Navbar from "../components/homepage/Navbar.svelte";
</script>


<!-- Body Main Components -->
<main>
<section class="bg-[#0a021a] m-6 rounded-xl">
<Navbar/>
<Hero/>
</section>
</main>


<!-- Style -->
<style lang="postcss">
  @reference "tailwindcss";
  :global(html) {
    background-color: theme(--color-gray-100);
  }
</style>