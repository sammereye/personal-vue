<template>
  <OtherProject v-for="otherProject in otherProjects" :key="otherProject.id" :id="otherProject.id" :title="otherProject.title" :description="otherProject.description" :image="otherProject.image" :imageAlt="otherProject.imageAlt" :link="otherProject.link" />
</template>

<script>
import OtherProject from './OtherProjectsProject.vue';
export default {
  name: 'OtherProjects',
  components: {
    OtherProject
  },
  data() {
    return {
      otherProjects: [
        {
          id: 1,
          title: 'The Planets',
          description: 'The Planets is a front-end project that allows you to discover all of the planets in our solar system. It utilizes React and TailwindCSS to create an interactive single-page application that allows visitors to view all of the planets, alongside wikipedia information and general stats.',
          image: '/assets/planets.webp',
          imageAlt: 'Image of The Planets Website',
          link: 'https://sammer.dev/planets'
        }
      ]
    }
  }
}
</script>