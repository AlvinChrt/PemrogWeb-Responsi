
<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="#hero">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#projects">My Project</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"></a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
    <div>
      <AboutSection />
      <HeroSection />
      <ProjectsSection />
    </div>
  </template>
  
  <style>
  .container-fluid{
    background-color: #3572EF;
    border-radius: 3px;
  }
  
  .nav-item{
    color: aliceblue;
  }
  
  </style>
  
  <script>
  import HeroSection from '~/components/HeroSection.vue';
  import AboutSection from '~/components/AboutSection.vue';
  import ProjectsSection from '~/components/ProjectsSection.vue';
  import ContactSection from '~/components/ContactSection.vue';
  
  export default {
    components: {
      HeroSection,
      AboutSection,
      ProjectsSection,
    }
    
  }
  
  </script>./Index.vue
  