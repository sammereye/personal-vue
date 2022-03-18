<template>
  <div class="flex flex-col mt-24">
    <div class="name text-3xl font-semibold mb-2 font-[Poppins] uppercase text-[#e8eaee]">Projects</div>
    <div class="bg-[#1aea9b] w-20 h-1.5 mb-4"></div>
    <Projects />
    <div class="name text-3xl font-semibold mt-20 mb-2 font-[Poppins] uppercase text-[#e8eaee]">Other Projects</div>
    <div class="bg-[#1aea9b] w-20 h-1.5 mb-8"></div>
    <OtherProjects />
  </div>  
</template>

<script>
  import Projects from './Projects/ProjectsIndex.vue';
  import OtherProjects from './Projects/ProjectsOtherProjects.vue';
  export default {
    name: 'Main',
    components: {
      Projects,
      OtherProjects,
    }
  }
</script>