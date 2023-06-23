<!--<template>-->
<!--  <div id="app">-->
<!--    <p>{{ message }}</p>-->
<!--  </div>-->
<!--</template>-->

<!--<script>-->
<!--export default {-->
<!--  data: function () {-->
<!--    return {-->
<!--      message: "Hello Vue!"-->
<!--    }-->
<!--  }-->
<!--}-->
<!--</script>-->

<!--<style scoped>-->
<!--p {-->
<!--  font-size: 2em;-->
<!--  text-align: center;-->
<!--}-->
<!--</style>-->




<template>
  <div id="app">
    <hello></hello>
  </div>
</template>

<script>
import Hello from './components/hello.vue';

export default {
  components: {
    Hello
  }
};
</script>

<style>
#app {
  font-family: Arial, sans-serif;
  text-align: center;
  padding: 20px;
}
</style>
