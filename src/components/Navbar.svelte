<script>
    let links = [
      { title: 'Home', href: '#' },
      { title: 'Latest Jobs', href: '#' },
      { title: 'Results', href: '#' },
      { title: 'Admit Card', href: '#' },
      { title: 'Answer Key', href: '#' },
      { title: 'Contact Us', href: '#' },
    ];
  </script>
  
  <nav class="bg-gray-800">
    <div class="container mx-auto px-4 py-2 flex justify-between items-center">
      <a href="#" class="flex items-center">
        <span class="text-xl font-bold text-white">Sarkari Result</span>
      </a>
  
      <ul class="flex space-x-4">
        {#each links as link}
          <li>
            <a href="{link.href}" class="text-white hover:text-gray-200 px-3 py-2 rounded-md">
              {link.title}
            </a>
          </li>
        {/each}
      </ul>
    </div>
  </nav>
  