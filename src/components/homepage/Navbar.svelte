<script>
	const navLinks = ['Real estate', 'E-commerce', 'Home Service', 'Dentist'];
</script>

<nav class="text-white lg:px-[145px] lg:py-1 mt-2">
	<section class="flex justify-between items-center pt-[20px] px-4">
		<div class="flex items-center space-x-2">
			<img src="/logo.png" alt="Logo" class="h-6 w-6 text-purple-500" />
			<span class="text-lg font-semibold">Dialleads</span>
		</div>

		<ul class="hidden justify-between md:flex gap-14 text-md font-medium">
			{#each navLinks as link}
				<li class="cursor-pointer text-gray-300 hover:text-purple-400 transition">{link}</li>
			{/each}
		</ul>

		<button
			class="ml-4 bg-gradient-to-r from-purple-600 to-purple-400 px-5 py-2 rounded-xl text-sm font-semibold hover:opacity-90 transition"
		>
			Contact us
		</button>
	</section>
</nav>
