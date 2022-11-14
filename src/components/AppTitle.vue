<script>
export default {
  name: 'AppTitle',
  data(){
    return{
      title: 'La mia prima App con Vite!'
    }
  }
}
</script>

<template>
  <div class="container">
    <h1>{{ title }}</h1>
  </div>
</template>

<style>
h1 {
  text-align: center;
  color: cornflowerblue;
}
</style>