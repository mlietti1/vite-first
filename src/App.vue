<script>

import AppTitle from './components/AppTitle.vue'

export default {
  name: 'App',
  components: {
    AppTitle
  },
  data(){
    return{
      title: 'Hello Vue + Vite'
    }
  }
}
</script>

<template>
  <div class="container">
    <span>Stampo titolo da component qui sotto:</span>
  </div>
  <AppTitle/>
</template>


<style>

</style>