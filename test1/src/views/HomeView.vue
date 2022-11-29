<template>
  <div>
    <h1>This is Home page</h1>
    <ShinCoder />
  </div>
</template>

<script>
import ShinCoder from '@/components/ShinCoder.vue';

export default {
  components: {
    ShinCoder
  },

  data() {
    return {
      name: 'Shin Coder'
    }
  }
}
</script>

<style scoped>
h1 {
  color: red;
}
</style>