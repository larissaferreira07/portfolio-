<script>
  const technologies = [
    { name: 'Python', icon: 'python.svg' },
    { name: 'PHP', icon: 'php.svg' },
    { name: 'JavaScript', icon: 'javascript.svg' },
    { name: 'Svelte', icon: 'svelte.svg' },
    { name: 'HTML', icon: 'html5.svg' },
    { name: 'CSS', icon: 'css3.svg' },
    { name: 'Tailwind', icon: 'tailwindcss.svg' },
    { name: 'MySQL', icon: 'mysql.svg' },
    { name: 'PostgreSQL', icon: 'postgresql.svg' },
    { name: 'Git', icon: 'git.svg' },
    { name: 'Linux', icon: 'linux.svg' },
  ];
</script>

<section id="technologies" class="my-8">
  <h2 class="text-2xl font-bold mb-4 border-b-2 border-yellow-200 pb-2">Tecnologias</h2>
  <div class="grid grid-cols-3 md:grid-cols-5 gap-4">
    {#each technologies as tech}
      <div class="flex flex-col items-center">
        <img src={`/icons/${tech.icon}`} alt={tech.name} class="w-12 h-12 mb-2" />
        <span class="text-sm">{tech.name}</span>
      </div>
    {/each}
  </div>
</section>

