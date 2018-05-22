<template>
  <div class="home">
    <img src="../assets/logo.png">
    <HelloWorld :msg="welcome"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  data () {
    return {
      welcome: "Welcome in a Vue World my dear friend!"
    }
  },
  components: {
    HelloWorld
  }
}
</script>

<style scoped>

</style>

