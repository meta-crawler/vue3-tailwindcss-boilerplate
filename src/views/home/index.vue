<template>
  <div class="home">
    <img class="m-auto" alt="Vue logo" src="./images/logo.png" />
    <HelloWorld msg="Welcome to Your Vue3 + Tailwind CSS Boilerplate" />
  </div>
</template>

<script lang="ts">
import HelloWorld from './components/hello-world.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
  },
  setup(): void {
    console.log(process.env.NODE_ENV)
  },
}
</script>
