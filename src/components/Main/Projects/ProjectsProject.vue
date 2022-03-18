<template>
  <div class="project flex lg:flex-row flex-col" :class="{ 'mt-4': id == 1, 'mt-20': id != 1 }">
    <div class="lg:w-[50%] w-full">
      <div class="name text-2xl font-medium mb-1 font-[Poppins] text-[#e8eaee]">{{ title }}</div>
      <div class="name text-sm font-medium mb-2 font-[Poppins] text-[#a0a6b1]">{{ startDate }} &mdash; {{ endDate }}</div>
      <div class="flex space-x-3 font-bold text-xs mb-5" >
        <Tag v-for="tag, i in tags" :key="i" :text="tag" />
      </div>
      <div class="w-[90%] font-[Inter] tracking-wide leading-9 text-[15px] text-[#e7e7ea]">{{ description }}</div>
    </div>
    <div class="lg:w-[50%] w-full flex items-center lg:mt-0 mt-5">
      <img v-if="!image.includes('.mp4')" :src="image" :alt="imageAlt" class="shadow-lg w-full rounded-md bg-gray-400" />
      <video v-else class="shadow-lg w-full rounded-md bg-gray-400" autoplay muted loop>
        <source src="/assets/tarkovhandbook.mp4" type="video/mp4">
      </video>
    </div>
  </div>
</template>

<script>
  import Tag from './ProjectsTag.vue';
  export default {
    name: 'Project',
    props: {
      id: Number,
      title: String,
      startDate: String,
      endDate: String,
      tags: Array,
      description: String,
      image: String,
      imageAlt: String
    },
    components: {
      Tag
    }
  }
</script>