<template>
  <div>
    <Title msg="La mia prima app con Vue CLI!"/>
    <Hero title="Standard Tooling for Vue.js Development" subtitle="Vue CLI aims to be the standard tooling baseline for the Vue ecosystem. It ensures the various build tools work smoothly together with sensible defaults so you can focus on writing your app instead of spending days wrangling with configurations. At the same time, it still offers the flexibility to tweak the config of each tool without the need for ejecting."/>
    <div class="image">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ0giye6b65OcnCQAUbbkTsgK7OxT4ytFa75eNxU6P3UYNHcUgTqM06eZf4w4Wy3e7HH6M&usqp=CAU" alt="Vue.js CLI">
    </div>
  </div>
</template>

<script>
import Title from './components/Title.vue';
import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    Title,
    Hero
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.image {
  max-width: 250px;
  margin: auto;
}
.image img {
  width: 100%;
}
</style>
