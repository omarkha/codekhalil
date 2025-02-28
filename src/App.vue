<template>
  <TopBar/>
  <HomePage />
</template> 

<script>
import HomePage from './components/HomePage.vue';
import TopBar from './components/TopBar.vue';


export default {
  name: 'App',
  components: {
    HomePage, TopBar
  }
}
</script>
 
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
