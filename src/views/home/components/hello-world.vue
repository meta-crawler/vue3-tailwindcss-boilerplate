<template>
  <div class="hello">
    <h1 class="text-2xl">{{ msg }}</h1>
  </div>
</template>

<script lang="ts">
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
}
</script>
