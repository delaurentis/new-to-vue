<!-- HTML --> 
<!-- Structure: Where does everything go? -->
<template>
  <div class="component">
    <button @click="incrementCount()">{{ msg }}: {{ count }}</button>
  </div>
</template>

<!-- JavaScript --> 
<!-- Functionality: What does it do? -->
<script>

export default {
  props: {
    msg: String,
  },
  data() {
    return {
      count: 0,
    }
  },
  methods: {
    incrementCount() {
      this.count++
    },
  },
  mounted() {
  },
}

</script>

<!-- CSS --> 
<!-- Style: How does it look? -->
<style scoped>

  button {
    font-size: 14px;
    opacity: 1;
    padding: 10px;
    background-color: #E5E5E5;
    border: 1px solid rgba(0, 0, 0, 0.25);
    border-radius: 5px;
    cursor: pointer;
  }
  button:hover{
   
  }
  button:active{
    background-color: #DFDFDF;
    transform: translate(1px, 1px);
  }

</style>