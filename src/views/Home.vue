<template>
  <body id="homebody">
  <div>
    <nav-menu></nav-menu>
    <router-view/>
  </div>
  </body>
</template>

<script>
  import NavMenu from '@/components/common/NavMenu'
  export default {
    name: 'Home',
    components: {NavMenu}
  }
</script>

<style scoped>
  #homebody {
    background:url("../assets/home/home_bg01.jpg") no-repeat;
    background-position: center;
    height: 100%;
    width: 100%;
    background-size: cover;
    position: fixed;
  }
  body{
    margin: 0px;
  }

</style>
