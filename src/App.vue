<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>
<style>
  img{
    display: block;
    width: 100%;
  }
  div, section, html, body{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }
</style>
