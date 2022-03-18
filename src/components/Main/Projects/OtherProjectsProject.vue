<template>
  <div class="other-project w-[400px] px-6 py-6 bg-[#1aea9b] rounded-lg shadow-lg">
    <img class="rounded-md shadow-md" :src="image" :alt="imageAlt" />
    <div class="font-[Poppins] text-[#141414] mt-4 mb-1 text-lg">{{ title }}</div>
    <div class="font-[Inter] text-[#2b2b2b] text-sm tracking-wide leading-6">{{ description }}</div>
    <a class="block w-full font-[Poppins] bg-[#a3f6d5] border-[#363e57] border-2 font-medium text-[#1d1d1d] rounded-md uppercase tracking-wide text-center py-2 mt-4 text-sm shadow-sm lg:hover:shadow-lg lg:hover:-translate-y-1 lg:cursor-pointer transition duration-300" :href="link" target="_blank" rel="noreferrer">{{`View ${title} Project`}}</a>
  </div>
</template>

<script>
export default {
  name: 'OtherProject',
  props: {
    id: Number,
    title: String,
    description: String,
    image: String,
    imageAlt: String,
    link: String
  }
}
</script>