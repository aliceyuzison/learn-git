<template>
  <div id="app">
    <div class='world' @click="handleClick">{{message}}</div>
    <!--<router-view/>-->
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      message: 'hello world'
    }
  },
  methods: {
    handleClick () {
      this.message = 'bye world'
    }
  }
}
</script>

<style scoped>
 .world {
   color: red;
 }
</style>
