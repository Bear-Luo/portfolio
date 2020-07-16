<template>
  <nav class="uk-navbar-container" uk-navbar uk-sticky="top">
    <div class="uk-navbar-center">
      <h1 class="uk-h2">Laura's Portfolio</h1>
    </div>
  </nav>
</template>

<script>
export default {
  data () {
    return {
    }
  }
}
</script>

<style>
  .uk-navbar-container:not(.uk-navbar-transparent) {
    background: linear-gradient(65deg, #e2ab36 0%, #85c6cc 15%, #a6d3aa 50%, #85c6cc 85%, #f59f7e 100%) !important;
    box-shadow: 0 0 15px rgba(0, 0, 0, .2);
  }
  h1.uk-h2 {
    font-family: 'Fredoka One', cursive, sans-serif;
    color: #fff;
    margin-block-start: .83em;
    text-shadow: 0 2px rgba(172, 111, 129 , .2);
    transition: all .2s linear;
  }
  .uk-active h1.uk-h2 {
    margin-block-start: .67em;
    margin-block-end: .67em;
    font-size: 1.5em;
    transition: all .2s linear;
  }
</style>
