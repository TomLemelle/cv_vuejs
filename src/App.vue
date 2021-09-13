<template>
  <Sidebar />
  <Main />

</template>

<script>
import Main from './views/Main.vue'
import Sidebar from './views/Sidebar.vue';

export default {
  name: 'App',
  components: {
    Main,
    Sidebar
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700&display=swap');

#app {
  font-family: 'Lato', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 1122px;
  height: auto;
  margin: 0 auto;
  display: flex;
  border: 1px solid black;
}

p {
  padding: 0;
  margin: 0;
}
</style>
