<template>
  <div class="home">
    <img class='logo' alt="Vue logo" src="../assets/logo.svg">
    <h2>{{ msg }}</h2>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  data () {
    return {
      msg: 'Technical Challenge'
    }
  }
};
</script>

<style lang='scss'>

.logo { 
  max-width: 500px; 
}
</style>