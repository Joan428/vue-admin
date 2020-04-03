<template>
  <div id="app">
    <Login></Login>
    <router-view/>
  </div>
</template>

<script>
import Login from 'views/login/Login'
export default {
  name: 'App',
  components: {
    Login,
  }
}
</script>

<style lang="scss">
@import './assets/css/main.scss';


</style>
