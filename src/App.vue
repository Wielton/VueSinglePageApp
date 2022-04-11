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
  box-sizing: border-box;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  width: 100%;
  height: 100%;
  align-items: center;
}
#headerdiv {
  height: 15vh;
}
#bodydiv {
  height: 100%;
  width: 100%;
}
#footerdiv {
  height: 10vh;
}
</style>
