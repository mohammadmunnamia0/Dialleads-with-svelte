<script>
  import { features } from './Features.js';
  import Icon from '@iconify/svelte';
</script>

<section class="py-16 text-center bg-white">
  <div class="mb-6">
    <span class="inline-block px-4 py-1 border border-gray-300 rounded-full text-sm text-gray-600">
      ✨ Features
    </span>
  </div>
  <h2 class="text-5xl font-bold mb-12">
    Why Diallead's AI Voice Assistants?
  </h2>

  <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 max-w-7xl mx-auto px-4">
    {#each features as { icon, title, description }}
      <div class="p-6 rounded-2xl bg-white text-left shadow-sm hover:shadow-md transition">
        <Icon icon={icon} width="36" height="36" class="text-purple-500 mb-4" />
        <h3 class="text-lg font-semibold mb-2">{title}</h3>
        <p class="text-gray-600 text-sm">{description}</p>
      </div>
    {/each}
  </div>
</section>
