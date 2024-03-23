<script>
    export let title;
    export let description;
  </script>
  
  <div class="p-4 border rounded shadow-lg bg-white">
    <h2 class="font-bold text-xl mb-2 text-center">{title}</h2>
    <ul class="text-gray-700 list-disc ml-6">
      {#if description}
        {#each description.split('.') as item}
          <li>{item.trim()}.</li>
        {/each}
      {/if}
    </ul>
  </div>
  