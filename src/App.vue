<template>
  <div>
    <div class="max-w-xl mx-auto flex flex-col p-6 bg-white rounded-lg shadow-xl">
      <div id="nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
      </div>
      <router-view />
    </div>
  </div>
</template>

<style lang="scss" src="./assets/styles/style.scss"></style>
