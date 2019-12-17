<template>
  <div class="home">
    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: "home",
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss" scoped>
  .home {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
</style>