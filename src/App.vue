<script>
import testa from './header.vue'
import navigation from './nav.vue'

export default {
  components: {
    testa,
    navigation,
  }
}
</script>
<template>
  <div class="container">
    <testa />
    <div class="content_place">
      <h1> CONTENT GOES HERE </h1>

    </div>
    <navigation />

  </div>
</template>
<style>
.content_place {
  background-color: black;
  color: white;
  padding: 3px 100px;
  margin-top: 20px;
}
</style>