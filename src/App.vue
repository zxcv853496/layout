<template>
  <div id="app">
    <NavBar />
    <router-view/>
  </div>
</template>


<script>
// @ is an alias to /src
import NavBar from './components/Nav/NavBar'

export default {
  name: 'app',
  components: {
    NavBar
  }
}
</script>