<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <h1 class="title">Hello World</h1>
  <p class="description">
    Welcome to your first web app.
  </p>
  <counter msg="Count is" />
</template>

<script>
import Counter from './components/Counter.vue'
  
// Options API
export default {
  components: {
    'counter': Counter,
  },
  props: {},
  data() {
    return {}
  },
  methods: {},
  mounted() {
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
h1 {
  color: black;
}
p {
  margin-bottom: 24px;
}
</style>
