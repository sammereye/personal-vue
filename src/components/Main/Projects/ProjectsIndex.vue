<template>
  <div class="projects-container">
    <Project v-for="project in projects" :key="project.id" :id="project.id" :title="project.title" :startDate="project.startDate" :endDate="project.endDate" :tags="project.tags" :description="project.description" :image="project.image" :imageAlt="project.imageAlt" />
  </div>
</template>

<script>
  import Project from './ProjectsProject.vue';
  export default {
    name: 'Projects',
    components: {
      Project
    },
    data() {
      return {
        projects: [
          {
            id: 1,
            title: 'Dig our RIS v2 (DORIS2)',
            startDate: 'February 2020',
            endDate: 'Ongoing',
            tags: ['Ruby on Rails', 'ElasticSearch', 'SQL Server'],
            description: 'Dig our RIS v2 (DORIS2) is an independently built Ruby on Rails web application that gives researchers and physicians at the IU School of Medicine the ability to query through roughly 20,000,000 radiology exams with less than a second of response time. The application utilizes ElasticSearch and SQL Server to give users the ablity to fine-tune their search requirements to tailor their exacts needs. Searches are utilized by researchers, administration and residents.',
            image: '/assets/doris2.webp',
            imageAlt: 'Image of DORIS2'
          },
          {
            id: 2,
            title: 'Tarkov Handboook',
            startDate: 'January 2022',
            endDate: 'Ongoing',
            tags: ['HTML', 'CSS', 'NodeJS', 'Electron'],
            description: 'Tarkov Handbook is an Electron application with NodeJS that allows users to click a hotkey and launch a small but detailed overlay on top of the game to search for in-game market prices, quest guides, interactive maps and more. During development, the Tarkov Handbook was in beta for public use which resulted in roughly 500 downloads and 3,000 YouTube views.',
            image: '/assets/tarkovhandbook.mp4',
            imageAlt: 'Video of TarkovHandbook'
          },
          {
            id: 3,
            title: 'RECIST Dashboard',
            startDate: 'January 2019',
            endDate: 'February 2020',
            tags: ['HTML', 'CSS', 'Ruby on Rails', 'SQL Server'],
            description: 'The RECIST Dashboard is an independently built Ruby on Rails web application that allows radiologists and oncologists to add patients, add associated lesions/tumors and enter in measurements each time they visit for an appointment. The measurement data is then used to track how the patient is progressing throughout their treatment. Prior to the launch of the RECIST Dashboard, radiology assistants were required to hand-write all patient data and store them within physical folders. This system dramatically increased workflow times and reduced human error by setting strict submission guidelines.',
            image: '/assets/recist.webp',
            imageAlt: 'Image of RECIST'
          },
        ]
      }
    }
  }
</script>