<template>
  <div class="hello">
    {{msg}}
  </div>
</template>

<script>
export default {
  name: 'app',
  components: {

  }, 
  data() {
    return {
      msg: 'Hello'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  * {
    box-sizing:border-box;
    margin:0;
    padding:0;
  }

  body {
    font-family:sans-serif, helvetica;
    line-height:1.4;
  }

</style>
