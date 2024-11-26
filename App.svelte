<script>
  import Header from './components/Header.svelte';
  import About from './components/About.svelte';
  import Contact from './components/Contact.svelte';
  import Services from './components/Services.svelte';
  import Technologies from './components/Technologies.svelte';
  import Experience from './components/Experience.svelte';
  import Projects from './components/Projects.svelte';
  import Education from './components/Education.svelte';
</script>

<main class="bg-gray-100 text-gray-800">
  <Header />
  <div class="container mx-auto px-4 py-8">
    <About />
    <Services />
    <Technologies />
    <Experience />
    <Projects />
    <Education />
    <Contact />
  </div>
</main>

<style global>
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap');
  
  :root {
    --primary-color: #f0e68c;
    --secondary-color: #e6e6e6;
  }

  body {
    font-family: 'Roboto', sans-serif;
  }
</style>

