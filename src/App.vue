<template>
  <div id="app">
    <Navbar />
    <Home />
  </div>
</template>

<script>
import Home from './components/Home.vue'
import Navbar from './components/Navbar.vue'

export default {
  name: 'App',
  data () {
    return {
    }
  },
  components: {
    Home,
    Navbar
  }
}
</script>

<style>
@import '~uikit/dist/css/uikit.min.css';

body, .uk-h1, .uk-h2, .uk-h3, .uk-h4, .uk-h5, .uk-h6, .uk-heading-2xlarge, .uk-heading-large, .uk-heading-medium, .uk-heading-small, .uk-heading-xlarge, h1, h2, h3, h4, h5, h6 {
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji", Helvetica, Arial, "PingFang TC", "Microsoft JhengHei", sans-serif;
}
</style>
