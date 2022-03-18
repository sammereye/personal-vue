<template>
  <div class="px-2 py-1.5 bg-[#1aea9b] rounded-md">{{ text }}</div>
</template>

<script>
export default {
  name: 'Tag',
  props: {
    text: String
  }
}
</script>