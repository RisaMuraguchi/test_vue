<template>
  <div id='hello'>
    {{ message }}
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello, Vue.js!'
    };
  }
};
</script>

<style scoped>
#hello {
  color: red;
}
</style>
