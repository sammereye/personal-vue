<template>
  <div class="flex lg:flex-row flex-col">
    <HeroHeader />
    <HeroEditor />
  </div>
</template>

<script>
import HeroHeader from './HeroHeader.vue';
import HeroEditor from './HeroEditor.vue';
export default {
  name: 'Hero',
  components: {
    HeroHeader,
    HeroEditor,
  }
}
</script>