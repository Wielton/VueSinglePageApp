<template>
  <div id="app">
    <PageHeader/>
    <PageBody/>
    <PageFooter/>
  </div>
</template>

<script>

import PageHeader from './components/PageHeader.vue'
import PageBody from './components/PageBody.vue'
import PageFooter from './components/PageFooter.vue'


export default {
  name: 'App',
  components: {
    PageHeader,
    PageBody,
    PageFooter
  }
}
</script>

<style>
#app {
  position: relative;
  box-sizing: border-box;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  align-items: center;
  background-color: rgba(119, 136, 153, 0.76);
  height: 97.5vh;
}
#headerdiv {
  height: 10%;
}
#bodydiv {
  height: 75%;
  display: grid;
  grid-template-columns: 1fr 2fr 1fr;
}
#footerdiv {
  height: 15%;
}
</style>
